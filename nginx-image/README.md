## Prerequisite
Docker must be installed

## Quick Start
1) Public repo in dockerhub
 <img width="1368" alt="image" src="https://user-images.githubusercontent.com/31353777/183261164-18fcedd8-9ee5-4ea9-95a1-40c10c16d848.png">


2) Build Docker image
```bash
 docker build -t nginx:1.0.0 .
```

3) Run docker container
```bash
docker run --name nginx -d -p 8080:80 nginx:1.0.0
```

4) Open browser, add url localhost:8080
<img width="1436" alt="image" src="https://user-images.githubusercontent.com/31353777/183261240-3a17345e-57d1-4482-849f-bd2f1d3f737f.png">

5) Tag docker images, with latest version
```bash
docker tag nginx:1.0.0 vanshmadan12/public-nginx:latest
```
6) Push docker image to docker hub
```bash
docker push vanshmadan12/public-nginx:latest
```
7) Validate it on docker hub or by docker pull
```bash
docker pull vanshmadan12/public-nginx:latest
```

<img width="1310" alt="image" src="https://user-images.githubusercontent.com/31353777/183261818-a2e43366-33c5-463c-897d-893547db55b2.png">






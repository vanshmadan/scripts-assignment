## Prerequisite
Docker must be installed


1) Public repo in dockerhub
 <img width="1368" alt="image" src="https://user-images.githubusercontent.com/31353777/183261164-18fcedd8-9ee5-4ea9-95a1-40c10c16d848.png">


2) Build Docker image
```bash
 docker build -t nginx:1.0.1 .
```

3) Run docker container
```bash
docker run --name nginx -d -p 8080:80 nginx:1.0.0
```

4) Open browser, add url localhost:8080
<img width="1436" alt="image" src="https://user-images.githubusercontent.com/31353777/183261240-3a17345e-57d1-4482-849f-bd2f1d3f737f.png">




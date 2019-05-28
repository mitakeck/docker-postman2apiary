# docker-postman2apiary

## setup container 

```
docker build -t mitakeck/postman2apiary .
```

## run

```
docker run -v `pwd`:/work mitakeck/hoge postman_collection.json index.html
```
# docker-postman2apiary

## setup container 

```
docker build -t mitakeck/postman2apiary .
```

## run

```
docker run -v `pwd`:/work mitakeck/postman2apiary postman_collection.json index.html
```
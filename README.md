# pressapi/php-alpine

build image

```bash
docker build -t pressapi/php-alpine .
```

Access the image

```bash
docker run -d --name press-api pressapi/php-alpine
docker exec press-api apk add bash
docker exec -it press-api bash
```

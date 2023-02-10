

## docker-compose command

```
docker-compose down
docker-compose up -d --no-deps --build web
```

```
docker buildx build --platform=linux/arm64 .
docker buildx build --platform=linux/amd64,linux/arm64,linux/arm/v7 .
docker buildx build --platform=darwin .

```

```
docker buildx build --platform=linux/arm64 -t my-docker-image .
```









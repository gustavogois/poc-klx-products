# Docker
```
docker-compose build
docker-compose up -d
docker-compose ps
docker-compose logs -f
docker-compose restart product
docker-compose up -d --scale product=1
docker-compose down

docker system prune -f --volumes
docker ps --format {{.Names}}
```

# Openapi Docs (Swagger)

http://localhost:8080/openapi/v3/api-docs
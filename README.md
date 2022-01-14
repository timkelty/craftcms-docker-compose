```
cp .env.example .env
docker-compose run --rm console composer install
docker-compose up -d
open http://localhost:8080/admin
```

# Ruby on rails app on docker. With - redis, sidekiq, postgres

## Require

* Ruby 2.4+
* Rails 5.1+
* Docker 1.11+ / Docker Compose API v2+

## FAQ

* Build and run the project with Docker Compose
```sh
docker-compose up --build
```

* Reset and Migrate the database (run this in a 2nd Docker-enabled terminal)
```sh
docker-compose exec website rails db:reset
docker-compose exec website rails db:migrate
```

# Enjoy

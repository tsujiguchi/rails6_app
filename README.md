# Rails6 Sample APP
このアプリケーションはRails勉強用です。

## Version
- Ruby 2.7.1
- Rails 6.0.3.1
- MySQL 8.0.20

## Install & Usage
### Setup Rails app on Docker
```
cp .env.dev.sample .env.dev

docker-compose build
docker-compose run --rm web bundle exec rails db:create
docker-compose run --rm web bundle exec rails db:migrate
```
### RUN
```
docker-compose up -d
```

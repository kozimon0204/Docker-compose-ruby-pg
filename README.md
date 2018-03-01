Docker-compose-ruby-postgres
====

Overview

Dockerとdocker-composeを使ってRuby、PostgreSQLの環境を作成する

Create a Ruby 2.5.0 and PostgreSQL 10.1 environment with Docker and docker-compose.

## Description
Docker 17.12.0

docker-compose 1.19.0

Ruby 2.5.0

PostgreSQL 10.1


## Demo
None

## VS. 
None

## Requirement
It needs these environments.

Docker 17.12.0

docker-compose 1.19.0

## Usage
docker-compose.ymlがあるディレクトリで以下のコマンドを実行

Run these command and create container where docker-compose.yml is located.

`docker-compose build`

`docker-compose up -d`

コンテナにログイン

Login to the container.

`docker-compose exec web bash`

Railsアプリを作成

Create rails application.

`rails new <[APP NAME]> -d postgresql -BT`


## Install
Do yourself.

## Contribution
Not yet.

## Licence

[MIT](https://github.com/kozimon0204/Docker-compose-ruby-pg/blob/master/LICENSE)

## Author

[Takahiro Koshika](https://github.com/kozimon0204)

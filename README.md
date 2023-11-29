# laravel-react-posting-app
## login command

    php
    docker exec -it laravel-api bash

    mysql
    docker exec -it mysql mysql -u root -p

    react
    docker compose exec front bash

## apiドキュメント関連

### ReDoc
http://localhost:3032/

### Swagger
http://localhost:3031/

### Prism
http://localhost:3030/

## React

### URL
http://localhost:3000/

### プロジェクト実行

コンテナに入る
`docker compose exec front bash`

プロジェクトを実行
`npm start`

## DB(Mysql)

### ログイン

コンテナに入る
`docker compose exec db bash`

dbに入る
`mysql -hlocalhost -p -uroot`
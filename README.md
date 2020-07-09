# CakePHP Practice

## CakePHP
- phpコンテナのビルド
```shell script
docker-compose up -d
```

- phpコンテナに入る
```shell script
docker exec -it fivews-php bash
```

- composerの使用
```shell script
composer --version
```

- 開発サーバー起動
  - http://127.0.0.1:8765/
```shell script
bin/cake server --host 0.0.0.0
```

- PHPUnit テスト
```shell script
vendor/bin/phpunit
```


## 参考
- [Docker Hub](https://hub.docker.com)
  - [composer - Docker Hub.html](https://hub.docker.com/_/composer)

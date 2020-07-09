# CakePHP Practice

## CakePHP
- phpコンテナに入る
```shell script
docker exec -it fivews-php bash
```

- 開発サーバー起動
  - http://127.0.0.1:8765/
```shell script
bin/cake server --host 0.0.0.0
```

## Composer
- [composer - Docker Hub.html](https://hub.docker.com/_/composer)

- Windows PowerShell 7
```shell script
docker run --rm --interactive --tty --volume ${PWD}:/app `
    composer --version --ignore-platform-reqs
```


## 参考
- [Docker Hub](https://hub.docker.com)
  - [composer - Docker Hub.html](https://hub.docker.com/_/composer)

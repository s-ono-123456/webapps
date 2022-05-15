# webアプリのホストコンテナ環境作成スクリプト

- apacheコンテナ
  httpdをcentos:7イメージに導入。

- tomcatコンテナ
  alpineのtomcatコンテナを利用。

- 利用方法
  docker-compose build
  docker-compose upコマンドによりwebアプリをホストできる。
  サンプルとして、http://localhost:80/exaples/にアクセスするとサンプルアプリにアクセスできる。
  
# django-docker-startkit
Docker x Djangoのプロジェクトを作成するときに毎回調べてしまっているので、テンプレ化したもの

## 環境
* Django: リリースの最新版がインストールされる
* Docker: Python3イメージ
* DB: sqlite3が入るので、RDB使う場合はプロジェクト作成後に設定

## コマンド
```
$ docker-compose run web django-admin startproject [プロジェクト名] .
```

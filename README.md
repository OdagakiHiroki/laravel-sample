# laravel-sample
## アプリケーションサーバーを作成
## webサーバーコンテナを作成(nginx)
## Laravelをインストール
appコンテナに入る
```
docker-compose exec app ash
```
laravelインストールコマンド
```
composer create-project --prefer-dist "laravel/laravel=6.0.*" .
```
バージョンの確認
```
php artisan -V
```
## データベースコンテナを作成（mysql)

### コマンド
dockerコンテナの起動、作成
```
docket-compose up -d --build
```
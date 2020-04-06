# laravel-sample
## アプリケーションサーバーを作成
## webサーバーコンテナを作成
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

### コマンド
dockerコンテナの起動、作成
```
docket-compose up -d --build
```
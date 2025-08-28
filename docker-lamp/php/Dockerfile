FROM php:7.4-apache

# 必要なパッケージをインストール
RUN apt-get update && apt-get install -y libsqlite3-dev

# SQLite拡張を有効化
RUN docker-php-ext-install pdo pdo_sqlite
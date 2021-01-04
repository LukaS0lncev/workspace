## Быстрый старт
```
git clone https://github.com/LukaS0lncev/workspace.git
cd workspace
docker-compose up -d
```
## Рабочая среда для Web разработки, на базе Docker
Статья в которой пошагово создается этот проект
[https://paimon.pro/blog/110-sreda-web-razrabotki-na-baze-docker-chast-1](https://paimon.pro/blog/110-sreda-web-razrabotki-na-baze-docker-chast-1)
### Какая цель проекта:
* Пошагово разобрать этапы создания контейнеров для рабочей среды
* Сделать полностью рабочий инструмент, скачал, запустил и работай.
* Дополнить рабочую среду 
### Что реализовано:
* Web сервер nginx (80 порт)
* php-fpm-alpine
    * php:5.6-fpm-alpine
    * php:7.1-fpm-alpine
    * php:7.2-fpm-alpine
    * php:7.3-fpm-alpine
* mysql
    * mysql:5.7
    * mysql:8.0.21
* Elasticsearch
    * Kibana

### Что будет реализовано в будущем:
* mongo
* postgres
* redis
>список будет дополняться
    
### Список расширений php [PHP Modules]:
* bcmath
* calendar
* Core
* ctype
* curl
* date
* dom
* exif
* fileinfo
* filter
* ftp
* gd
* gettext
* hash
* iconv
* intl
* json
* libxml
* mbstring
* mongodb
* mysqli
* mysqlnd
* openssl
* pcntl
* pcre
* PDO
* pdo_mysql
* pdo_pgsql
* pdo_sqlite
* pgsql
* Phar
* posix
* readline
* redis
* Reflection
* session
* SimpleXML
* soap
* sodium
* SPL
* sqlite3
* standard
* tokenizer
* xdebug
* xml
* xmlreader
* xmlwriter
* xsl
* Zend OPcache
* zip
* zlib

### Список установленных пакетов в контейнеры php-fpm через DockerFile:
  *  libintl 
  *  build-base 
  *  zlib-dev 
  *  cyrus-sasl-dev 
  *  libgsasl-dev 
  *  oniguruma-dev 
  *  procps 
  *  imagemagick 
  *  patch 
  *  bash 
  *  htop 
  *  acl 
  *  apk-cron 
  *  augeas-dev 
  *  autoconf 
  *  curl 
  *  ca-certificates 
  *  dialog 
  *  freetype-dev 
  *  gomplate 
  *  git 
  *  gcc 
  *  gettext-dev 
  *  icu-dev 
  *  libcurl 
  *  libffi-dev 
  *  libgcrypt-dev 
  *  libjpeg-turbo-dev 
  *  libpng-dev 
  *  libmcrypt-dev 
  *  libressl-dev 
  *  libxslt-dev 
  *  libzip-dev 
  *  linux-headers 
  *  libxml2-dev 
  *  ldb-dev 
  *  make 
  *  musl-dev 
  *  mysql-client 
  *  openssh-client 
  *  pcre-dev 
  *  ssmtp 
  *  sqlite-dev 
  *  supervisor 
  *  su-exec 
  *  wget 
  *  nodejs 
  *  npm  
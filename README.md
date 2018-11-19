# taxation

this micro-project calculates corporate taxes according to their type of categories
technologies: php7, symfony4, mysql

use example in config/taxation.sql, instead of running step 5

## installation setup 
### 1- get the repository from github
git clone https://github.com/debian125/taxation.git

### 2- install vendor
composer install

### 3- change DB login/pass in .env file

### 4- create database
php bin/console doctrine:database:create

### 5- update database: make tables with colomns, etc
php bin/console doctrine:schema:update --force

### 6- run the app 
php bin/console server:run

### 7- access the app in browser
http://127.0.0.1:8000 

let it guide you !
<!-- to run project  -->

cd project-name
composer install 

<!-- create application key -->
php artisan key:generate

php artisan migrate
php artisan db:seed


php artisan serve


<!-- in .env change sql_connections  -->
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=ecommerce   db name
DB_USERNAME=phpmyadmin  mysql user name
DB_PASSWORD=root        mysql password
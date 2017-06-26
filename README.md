# Laravel-REST-API

First download the project.

git clone https://github.com/MiroslavMogus/laravel-rest-api.git laravel-rest-api

cd laravel-rest-api

Change the DB details in the .env file and also in the /config/database.php

Then open CMD

Go to the directory where the project is

Enter the command composer install

Enter the command php artisan migrate

After that you can try to execute multiple JSON requests with POSTMAN or other tools like CURL to get the response

For example:
http://rest-api.app/api/buyers - list all buyers
http://rest-api.app/api/users/ - list all users

http://rest-api.app/api/buyers?page=2 - pagination implementatin to get second page of user list

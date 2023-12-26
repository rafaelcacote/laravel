Installation
Warning Make sure to follow the requirements first.

Here is how you can run the project locally:

Clone this project

git clone https://github.com/rafaelcacote/laravel.git
Go into the project root directory

cd laravel
Copy .env.example file to .env file

cp .env.example .env
Create database (you can put any database name)

Go to .env file

set database credentials
Make sure to follow your database username and password

Install PHP dependencies

composer install
Generate key

php artisan key:generate

php artisan migrate

php artisan db:seed

this command will create 2 users (admin and normal user):

cpf: 00000000000 , password:123

Run server

for valet users visit velflix.test in your favorite browser

php artisan serve

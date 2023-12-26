<a name="installation"></a>

## Installation

> **Warning**
> Make sure to follow the requirements first.

Here is how you can run the project locally:

1. Clone this repo

   ```sh
   git clone https://github.com/rafaelcacote/laravel.git
   ```

1. Go into the project root directory

   ```sh
   cd laravel
   ```

1. Copy .env.example file to .env file
   ```sh
   cp .env.example .env
   ```
1. Create database `db_system` (you can change database name)

1. Go to `.env` file

   - set database credentials (`DB_DATABASE=`, `DB_USERNAME=`, `DB_PASSWORD=`)
     > Make sure to follow your database username and password

1. Install PHP dependencies

   ```sh
   composer install
   ```

1. Generate key

   ```sh
   php artisan key:generate
   ```

   ```

   ```

1. Run migration
   ```
   php artisan migrate
   ```
1. Run seeder

   ```
   php artisan db:seed
   ```

   this command will create 1 users (admin user):

   > user: 00000000000 , password: 1234678

1. Run server

   > for valet users visit `localhost:8000` in your favorite browser

   ```sh
   php artisan serve
   ```

1. Visit `localhost:8000` in your favorite browser.

   > Make sure to follow your Laravel local Development Environment.

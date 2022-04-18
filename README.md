1) composer install
2) rename .env.example file into .env
3) Open your .env file and change the database name (DB_DATABASE) to whatever you have, username (DB_USERNAME) and password (DB_PASSWORD) field correspond to your configuration
4) Run php artisan key:generate
5) Run php artisan migrate
6) Run php artisan serve
7) Go to http://localhost:8000/

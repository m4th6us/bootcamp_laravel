# bootcamp_laravel
in directory bootcamp_laravel/chirper/
web application developed using documentation for laravel

# install dependencies for application laravel (backend)
in directory bootcamp_laravel/chirper/
composer install

# install dependencies for application Vite.js (frontend)
npm install

# for run migrations
php artisan migrate

# config .env
DB_CONNECTION=sqlite

check if you have the sqlite3 driver installed, if not, run this command:
sudo apt-get install php-sqlite3

# run application
in directory bootcamp_laravel/chirper/

run this commands:
php artisan serve - start laravel
npm run dev - start Vite.js


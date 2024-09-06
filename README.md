# PPK-HMD-Dev

Installation
Clone the repo locally:

git clone https://github.com/mhmdfathan/PPK-HMD-Dev.git
cd expense_tracker
Install PHP dependencies:

composer install
Setup configuration:

cp .env.example .env
Generate application key:

php artisan key:generate
Edit .env and set your database connection details.

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=expense_tracker
DB_USERNAME=root
DB_PASSWORD=
Run database migrations:

php artisan migrate
Run database seeder:

php artisan db:seed
Run the dev server (the output will give the address):

php artisan serve
You're ready to go! Visit Expense Tracker in your browser, and login with:

Username: admin@gmail.com
Password: password

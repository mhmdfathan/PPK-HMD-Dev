# PPK-HMD-Dev

## Installation

1. **Clone the Repository**

```
git clone https://github.com/mhmdfathan/PPK-HMD-Dev.git 
cd PPK-HMD-Dev
```

3. **Install PHP Dependencies**

```
composer install
```

4. **Setup Configuration**

Copy the example environment file to create your `.env` file:
```
cp .env.example .env
```
Edit the `.env` file and set your database connection details:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=expense_tracker
DB_USERNAME=root
DB_PASSWORD=
```

5. **Generate Application Key**
```
php artisan key:generate
```

6. **Run Database Migrations**
```
php artisan migrate
```

7. **Run Database Seeder**
```
php artisan db:seed
```

8. **Run the Development Server**
```
php artisan serve
```
The output will provide the address where the application is accessible.

## Access the Application

Visit Expense Tracker in your browser and log in with the following credentials:
```
Username: admin@gmail.com
Password: password
```

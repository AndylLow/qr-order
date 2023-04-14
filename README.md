# qr-order
QR Code system for online ordering, made for restaurants.

# Admin Panel

## Steps

1. Start MySQL Server in port 3306, make sure database named "laravel" is created. If not, you can simply enter these commands:

    ```bash
    mysql -u root
    ```
    Then create the database:
    ```sql
    CREATE DATABASE laravel;
    ```
2. Run Vite development server.

    ```bash
    npm run dev
    ```
3. Run project:

    ```bash
    php artisan serve
    ```
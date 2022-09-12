# Blog Project

This blog project was developed along the studying of Jeffrey Way's course [Laravel From Scratch](https://laracasts.com/series/laravel-8-from-scratch).

## How to install the application:

1. **Clone the project repository** to your machine

2. On the terminal, in the project's folder, run
    ```
    $ composer install
    ```
to **install the app's dependencies**

3. In your prefered MySQL DMBS, **create the database for the project** with
   ```
   create database dbname;
   ```

4. Go to https://mailchimp.com/developer/marketing/guides/quick-start/, and https://mailchimp.com/developer/marketing/guides/create-your-first-audience/, then follow the instructions to create an account and **gather informations for newsletter configuration purposes**.

5. **Configure the .env file** with appropriate database and mailchimp information

6. **Run the migrations and seeder** command on the terminal **to create and populate the needed tables**,  with
   ```
   $ php artisan migrate:fresh --seed
   ```
7. Go to AppServiceProvider to **define the amdministrator username**

8. To **open the app** on your browser, run

   ```
   $ php artisan serve
   ```
9.  **Have fun! :)**

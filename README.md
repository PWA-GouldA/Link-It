# Link-It

Demonstration application development using Laravel.

## Steps taken

1)  Create new application: 
    - open terminal, change into folder to host application
    - `laravel new link-it`
    - `cd link-it`
    - `php ./artisan serve`
    - open `http://localhost:8000`
    - open a new terminal and change into the `link-it` folder
2)  Create database and database user
    - using whichever system you wish, create a new database and database user
    - create a database (eg: `tafeos_linkit`)
    - create the username and password (eg: `tafeos_linkit` and `Secret1`)
    - remember to give the user the access to the database created
3)  Open the Application code
    - open your preferred editor and open the `link-it` folder
    - you will need this for following steps  
    - open the `.env` file and edit the `DB_PASSWORD`, `DB_USERNAME` and `DB_DATABASE` to set them
      the same as database details you set in the previous step
    - If using version control, commit the changes
4)  Migrate the User Databases
    - in the second terminal, use the `artisan migrate` command
    - if you have any errors, this will because of your mysql username/password
    - this creates users and password_resets tables
5)  Create Authentication basic framework
    - `artisan make:auth`
    - This creates the 'Authentication scaffolding'
        - `resources/views/layouts` including the `app` blade file
        - `resources/views/auth` including `login`, `register` and `verify` blade files
        - `resources/views/auth/passwords` including `email` and `reset` blade files
        - `resources/views` including the `home` blade file
        - `app/Http/Controllers/Auth` including `ForgotPassword`, `Login`, `Register`, 
          `ResetPassword` and `Verification` controllers.
        - `app/Http/Controllers/` including the `Home` controller.
        - `app/Http/Controllers/`
        - `routes/` adds authentication to the `web.php` and `api.php` routes files.
    - 
6)  ...    
    -
7)  ...
    -

    
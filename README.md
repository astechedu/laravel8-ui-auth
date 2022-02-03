# laravel8-ui-vue
Laravel-8 with laravel ui &amp; vue
Laravel 8 Authentication with Laravel UI

    Step 1: Set Up Laravel Project.
    Step 2: Set Up Database Details in ENV.
    Step 3: Install Laravel UI.
    Step 4: Step up Auth Scaffolding.
    Step 5: Run npm install && npm run dev command.
    Step 6: Migrate your database.


Step 1: Set Up Laravel Project

    composer create-project --prefer-dist laravel/laravel larainfo

  
Step 2: Set Up Database Details in ENV

   .env

	DB_CONNECTION=mysql
	DB_HOST=127.0.0.1
	DB_PORT=3306
	DB_DATABASE=database_name
	DB_USERNAME=database_user_name
	DB_PASSWORD=database_password


Step 3: Install Laravel UI

	composer require laravel/ui



Step 4: Step up Auth Scaffolding 

	use anyone for you requirements

	php artisan ui bootstrap --auth
	php artisan ui vue --auth
	php artisan ui react --auth


Step 5: Run npm install && npm run dev command

npm install && npm run dev



Step 6: Migrate your database

 	php artisan migrate

Now our Laravel 8 authentication system is ready. you can run serve 

 	php artisan serve

# Prms_Project_Source_Code
Project Source Code for Patient Record Management System for Komfo Anokye Teaching Hospital
Before you Run the application there are some configurations phases to follow

**What to do after cloning the source code*
1.	Cd into the directory on the CLI
2.	Install composer dependencies
a.	composer install
3.	Install NPM dependencies
a.	npm install
4.	Create a copy of the .env.exmaple to .env
5.	Generate Key
a.	php aritisan key:generate
6.	Create a database in your phpadmin
7.	Update the DB name in the .env file
8.	Migrate database
a.	php artisan migrate db:seed


# KCCC - Credit Consulting Software. 

* [Installation](#Installation)

* [Instructions](#Instructions)

## Installation
1. Point to an existing repository and make a copy of that repository to the local filesystem;
	```
	**git clone https://gitlab.com/saran.fc/kccc.git**
	```
2. Change the current working directory to kccc
	```
	__cd kccc__
	```
3. To install the defined dependencies, run the installer command;
	```
	__composer install__
	```
4. Create the database for the project
5. Copy “.env.example” file and rename as “.env”  and specify database name and credentials
6. Set the APP_KEY value in .env file;
    ```
    php artisan key:generate
    ```
7. Create tables in the database using migration
	```
	php artisan migrate:fresh --seed
	```

## Instructions
Follow the above steps carefully then run the application.
```
	php artisan serve
```

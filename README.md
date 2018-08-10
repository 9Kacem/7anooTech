# 7anooTech
#### An e-commerce plateform adapted to the _Algerian_ market.

This project is one of ESI Sidi Bel Abbes 2nd year projects; It consists of creating an e-commerce web platform that should be useful, secure and easy to use by both Algerian business owners and their clients.

_Screenshots can be found here:_ https://github.com/9Kacem/7anooTech/blob/master/7anooTechScreenShots/README.md

## Installation:
- This project is built on Laravel, so make sure that you already have [PHP (>=7.1.3)](http://php.net/manual/en/install.php) and [Composer](https://getcomposer.org/download) installed.

- Edit `/etc/php/php.ini` and uncomment	`extension=mysqli.so` and `extension=pdo_mysql.so`

- Clone this repository by typing this command on your terminal:
	`https://github.com/9Kacem/7anooTech.git`

- Navigate to the project folder `cd 7anooTech/`
- Run `composer install` on your terminal
- Rename the `.env.example` file to `.env` on the project folder.
- In the `.env` file, change **DB_DATABASE** value to your database name. **DB_USERNAME** and **DB_PASSWORD** fields also should be changes to correspond to your DB configuration. On XAMPP, by default the user is `root` and the password is empty.
- Now Run the following commands:
-  `php artisan key:generate`
-  `php artisan migrate --seed`
-  `php artisan storage:link`

_Enabling the PDF Functionality:_

- run `sudo cp vendor/h4cc/wkhtmltopdf-amd64/bin/wkhtmltopdf-amd64 /usr/local/bin/wkhtmltopdf`
- run `sudo chmod +x /usr/local/bin/wkhtmltopdf`
- if it didn't work contact me (renken) and/else read [the official installation guide](https://github.com/barryvdh/laravel-snappy)

_Serving:_ 
- run: `php artisan serve`
> by this point the project is served locally and can be visited from your browser.

_Admin Access:_ 
To try the admin features (Dashboard, CRUD.. etc) log in to the website using these credentials:
- email: admin@email.com
- password: secret

## Team Members:
- AMAR BENSABER MOHMAED
- AZZAZ RAHMANI OUSSAMA
- BOUSSEKAR KACEM
- GOUMEIDA AHMED SEYF-EDDINE 
- IFFEROUDJENE MOULOUD
- MESSABIH OUSSAMA

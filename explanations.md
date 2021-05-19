# explaining-laravel7
Laravel is a simple using programming PHP build system, 


links: 
https://getcomposer.org/
https://laragon.org/download/index.html
https://windows.php.net/download#-7.4
https://www.phpmyadmin.net/downloads/

for the installation of laravel 7 the first thing u need is laragon

the second thing u need is the php version 7.4

then if u have downloaded laragon and the right php version u can get to install the php to laragon.

also u can get the right phpmyadmin version installed 7.9.5

to install the correct version open an new project map in laravel/www
call it project:
open this with visualstudio code
get a new terminal going.
composer create-project laravel/laravel ./ "7.*" --prefer-dist
enter this comment.

now that the database is created and the laravel project u can start.
enter the database name in the .env file.
in your laragon edit the public file.

for bootstrap:
composer require laravel/ui
php artisan ui bootstrap --auth
npm install
npm run dev

to create a full model:
php artisan make:model --all **NAME**




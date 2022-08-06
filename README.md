Laravel CMS using Vanilla PHP Views
This repository is copy of the simple PHP CMS except the CMS has been converted to Laravel.

A few notes regarding the CMS:

The CMS uses the public storage driver, make sure to update your .env file to:

FILESYSTEM_DRIVER=public
The database setup includes migrations and seeding. Run the following command to initialize the database:

php artisan migrate:refresh --seed
All user acocunts will have the default password of "password".

Tutorial Requirements:
Visual Studio Code or Brackets (or any code editor)
Laravel
Full tutorial URL: https://codeadam.ca/learning/php-cms-laravel.html


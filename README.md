# Laravel-Cloudinary
Make Uploading Images in Laravel using Cloudinary

## If You Want to Start
1. Copy the .env.example File to .env
2. Install all packages to run

```sh
$ composer install
```

3. setup the database. Then the contents of the configuration are `.env` according to the database settings. Example :

```sh
...
DB_DATABASE=your_database
DB_USERNAME=username
DB_PASSWORD=your_password
...
```

4. Run the following command :

```sh
$ php artisan key:generate
$ composer dump-autoload
$ php artisan storage:link
```

5. If you want to run the application, run the following command:

```sh
$ php artisan serve
```

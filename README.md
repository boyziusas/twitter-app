# twitter-app

## Installation

Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/8.x/installation/)

//
PHP ≥ 8.0.3


Clone the project repository by running the command below if you use SSH

```
git clone git@github.com:boyziusas/twitter-app.git
```

If you use https, use this instead

```
git clone https://github.com/boyziusas/twitter-app.git
```

Switch to the repo folder

```
cd twitter-app
```

Install all the dependencies using composer

```
composer update
```

Copy the example env file and **make the required configuration changes and fill missing entries from developer.twitter.com page** in the .env file

```
cp .env.example .env
```

Generate a new application key

```
php artisan key:generate
```

Don't forget to run node commands

```
npm install && npm run dev
```
Change database entries in the .env file and in path config/database make it utf8 standart

```
DB_DATABASE=oxontweet
```

Start the local development server

```
php artisan serve
```

You can now access the server at http://127.0.0.1:8000

**Used command list**

```
git clone git@github.com:boyziusas/wapp-chat.git
cd twitter-app
composer update
cp .env.example .env
php artisan key:generate
npm install
npm run dev
php artisan serve 
```

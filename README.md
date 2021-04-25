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

Copy the example env file and **make the required configuration changes by filling missing entries from developer.twitter.com page** in the .env file. You need to add these
lines: TWITTER_CLIENT_ID=your_client_id_or_consumer_key
TWITTER_CLIENT_SECRET=your_secret_code
TWITTER_CALLBACK_URL=http://127.0.0.1:8000/login/twitter/callback

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

Start the local development server

```
php artisan serve
```

You can now access the server at http://127.0.0.1:8000

**Used command list**

```
git clone git@github.com:boyziusas/twitter-app.git
cd twitter-app
composer update
cp .env.example .env
php artisan key:generate
npm install
npm run dev
php artisan serve 
```

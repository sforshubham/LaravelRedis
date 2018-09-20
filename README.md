# LaravelRedis

## Session Management with Redis
- This is a basic program that connect to a redis session, update the session content, do a basic auth, then logout and clear redis.

## Steps to follow
- Install laravel and composer
- Install redis server on your machine
- Install php client for redis with composer command - "composer require predis/predis"
- Run migration command - "php artisan migrate"
- Run make authentication command - "php artisan make:auth"
- Start artisan server - "php artisan serve"
- Hit the development server url in browser
- Register a user
- Login with newly created user
- Check data in redis with cli command "GET {key}" or hit "KEYS *" to get list of keys
- At last, logout
- Check if the key in redis is unset
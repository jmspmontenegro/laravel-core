## My Laravel base for applications

Laravel is my favorite framework, and this is my base repository for project development . I use it to start my projects.

## What have here?

I will add new packages as I discover and learn new possibilities, but always keeping it functional. My goal is always to have a complete base. 

- Laravel 8
- Laravel Tinker
- Docker

## How can i use it?

Follow these steps:

1. Clone this repository.
2. Install Docker and Docker Compose (ok, i suppose you know how to do that 😊).
3. Start containers:
```
docker-compose up -d
```
4. Access nginx container terminal:
```
docker exec -it nginx bash
```
5. Navegate to nginx directory and install Laravel:
```
cd /usr/share/nginx/
composer install
```
6. Create symbolic link and generate laravel key:
```
ln -s public html
php artisan key:generate
```
7. And it's done! Just look on your http://localhost:8080 

## And now?

Well, I know I can be even better, but I'm on the learning journey so that's it.
tks :)

Done with

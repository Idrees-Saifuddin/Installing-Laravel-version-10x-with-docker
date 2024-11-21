

# Laravel Docker Starter Kit
- Laravel v10.x
- PHP v8.2.x
- MySQL v8.1
- MariaDB v10.11
- phpMyAdmin v5.x
- Mailpit v1.x
- Node.js v18.x
- NPM v10.x
- Yarn v1.x
- Vite v5.x
- Rector v1.x
- Redis v7.2.x

# Requirements
- Stable version of [Docker](https://docs.docker.com/engine/install/)
- Compatible version of [Docker Compose](https://docs.docker.com/compose/install/#install-compose)

# How To Deploy

### For first time only !
- `docker compose up -d --build`
- `docker compose exec php bash`
- `composer setup`

### From the second time onwards
- `docker compose up -d`

# Notes

### Laravel App
- URL: http://localhost

### Basic docker compose commands
- Build or rebuild services
    - `docker compose build`
- Create and start containers
    - `docker compose up -d`
- Stop and remove containers, networks
    - `docker compose down`
- Stop all services
    - `docker compose stop`
- Restart service containers
    - `docker compose restart`
- Run a command inside a container
    - `docker compose exec [container] [command]`

### Useful Laravel Commands
- Display basic information about your application
    - `php artisan about`
- Remove the configuration cache file
    - `php artisan config:clear`
- Flush the application cache
    - `php artisan cache:clear`
- Clear all cached events and listeners
    - `php artisan event:clear`
- Delete all of the jobs from the specified queue
    - `php artisan queue:clear`
- Remove the route cache file
    - `php artisan route:clear`
- Clear all compiled view files
    - `php artisan view:clear`
- Remove the compiled class file
    - `php artisan clear-compiled`
- Remove the cached bootstrap files
    - `php artisan optimize:clear`
- Delete the cached mutex files created by scheduler
    - `php artisan schedule:clear-cache`
- Flush expired password reset tokens
    - `php artisan auth:clear-resets`

# TODO
- Improve environment 
- Add more containers


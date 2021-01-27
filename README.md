
## Example LEMP using docker compose

This example LEMP using docker compose with image Alpine Linux, Nginx, Mysql 5.7, PHP-fpm 7.4


### Running build command to build docker compose
'''
docker-compose build
'''

### After success the start the container
'''
docker-compose up -d
'''

### To pass command to container 
'''
docker-compose exec php php /var/www/artisan migrate
'''

## Reference
https://dev.to/aschmelyun/the-beauty-of-docker-for-local-laravel-development-13c0

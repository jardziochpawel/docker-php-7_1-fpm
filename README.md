# docker-php-7_1-fpm
    php:
        image: zipek91/docker-php-7_1-fpm
        expose:
            - "9000"
        volumes:
            - /path/to/project/:/var/www
            - /path/to/project/logs:/var/www/project/logs

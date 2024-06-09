FROM bitnami/laravel:10

WORKDIR /app

COPY ./app /app/

# ENV COMPOSER_ALLOW_SUPERUSER=1

# RUN composer install

EXPOSE 8000

CMD [ "php", "artisan", "serve", "--host=0.0.0.0", "--port=8000" ]
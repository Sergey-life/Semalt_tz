Запуск:

1. Скачать. В скачаной папке открыть терминал. Ввести команду: docker-compose build && docker-compose up -d
2. Вводим: composer dump-autoload
3. Вводим: docker-compose exec php php /var/www/html/artisan migrate
4. Вводим: docker-compose exec php php /var/www/html/artisan db:seed
5. Вводим в браузере: localhost:8088
6. phpMyAdmin: localhost:8008 
(log: homestead, pas: secret)

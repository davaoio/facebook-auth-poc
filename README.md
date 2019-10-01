##FACEBOOK AUTH POC

* Clone then `cd` inside the folder and run the following commands in order.
* `composer install`
* `git clone https://github.com/Laradock/laradock.git`
* `cd laradock`
* `cp env-example .env`
* Then inside the laradock folder, open its `.env` file and change `MYSQL_VERSION=latest` to `MYSQL_VERSION=5.7`
* `docker-compose up -d nginx mysql` then wait for awhile
* `php artisan migrate`
* `npm install && npm run dev`
* Set Facebook Keys on the `.env` file.
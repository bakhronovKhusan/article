## create folder 'database', logs/nginx/error.log
after folder actions <br>
--database <br>
--docker <br>
--logs/nginx/error.log <br>
--wwww <br>
--docker-compose.yml <br>
## For Install

docker-compose up -d

## For work with console

docker exec -it test-test-1 bash 

you work with artisan and other command in this place 

## If Have permission problem

1. docker exec -it test-test-1 bash
2. sudo chown -R $USER:www-data storage
   sudo chown -R $USER:www-data bootstrap/cache
   chmod -R 775 storage
   chmod -R 755 bootstrap/cache

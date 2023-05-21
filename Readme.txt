Technology Used:
1. PHP
2. Docker
3. HTML
4. CSS/Bootstrap
5. PHPUnit



----------------------------------------------------------------------------------------------------------

1. To setup docker use the below command.
docker-compose build

2. Use the below command to make sure all services are up and running.
docker-compose up -d

3. Run composer install
docker-compose exec -T web-server composer install

4. Run application from browser
http://127.0.0.1:8080/

5. To run the PHPUnit test use the below command
docker-compose exec -T web-server phpunit tests/MapsTest.php
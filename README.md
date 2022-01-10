
## Web App 

* Laravel PHP
* MySQL

 
## Installation for Server

 - clone the repository.
 - cd AttendanceMS-Server
 - docker run --rm -v $(pwd):/app composer install
 - docker-compose up -d 
 - docker-compose exec web php artisan migrate
 - docker-compose exec web php artisan key:generate 
 - open http://localhost:8080/
 - done
 
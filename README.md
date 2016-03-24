docker-laravel
==================

Dockerized laravel. The container include apache server with php 7.0 and mbstring,pdo_mysql,pdo_pgsql,gd php extensions. 

Your laravel application must be in a local directory e.g. "/c/Users/dilaverd/myapp/phootogram", and please add to the following command, the directory specified below.

# Run container
docker run --name container_name \
-v /c/Users/dilaverd/myapp/phootogram:/var/www/html \
-p "8000:80" \
ddemirel/docker-laravel

After that, go the url, e.g. ```http://docker_machine_ip_address:8000/```

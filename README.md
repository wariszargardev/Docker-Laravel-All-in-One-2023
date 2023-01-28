# Docker All In One Setup
## How to setup docker
```
https://docs.google.com/document/d/1Ux02TLVBbjC5CjbJacUX4RsRDdh-4AGnLoyRQeicWl0/edit?usp=sharing
```
# 1. MYSQL 
## MYSQL Commands 
```
mysql -u root(mysql root user name) -p
password: root 
```

##  MYSQL Listing All DB
```
show databases;
```

# 2. Php my admin
## Username root & password is root

# 3. Nginx
```
docker ps
# Non window system
docker exec -it container_id bash
# window
winpty docker exec -it container_id bash
cd /var/www/html
ls 
```

# 3. PHP
```
docker ps
# Non window system
docker exec -it container_id bash
# window
winpty docker exec -it container_id bash
go to /var/www/html
composer install 
php artisan migrate 
```
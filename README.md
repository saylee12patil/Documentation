# MariaDB Setup 

Explains how to set up MariaDB, create a database
## 1. Install MariaDB

Installing MariaDB 

```shell
apt update
apt install mariadb-server -y
```

## 2. Clone the repository

```shell
git clone 
```
## 4. Enter inside database container
docker exec -it <container_id> bash

## 3. Login to MySQL
mysql -u root -p

## 4.Create database
CREATE DATABASE student_db;

## 5 . Backend connection details
DB_USER=<your_username>
DB_PASS=<your_password>
DB_PORT=3306
DB_NAME=student_db
DB_HOST=<database_container_ip>

```shell
EXIT;
```


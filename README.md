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

Follow the prompts to:
Set a root password.
Remove insecure default users and test databases.
Disable remote root login.

## 3. Setting Up the Database

Open terminal and login to MariaDB:

```bash

mysql -u root -p
```

Enter the root password when prompted.

Create a new database and user:

```sql
CREATE DATABASE student_db;
GRANT ALL PRIVILEGES ON springbackend.* TO 'username'@'localhost' IDENTIFIED BY 'your_password';
```
EXIT;
```


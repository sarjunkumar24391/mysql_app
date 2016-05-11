Usage: 
-------------------------
docker run -d -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=defaultdb -e MYSQL_USER=user -e MYSQL_PASSWORD=password -p <host_ip>:<host_port>:3306 sarjunkumar24391/mysql_app:<tag>

SQL Syntax:
-------------------------
http://www.tutorialspoint.com/mysql

Environment variables:
-------------------------
MYSQL_ROOT_PASSWORD: The password for the root user. Defaults to a blank password
MYSQL_DATABASE: A database to automatically create. If not provided, does not create a database.
MYSQL_USER: A user to create that has access to the database specified by `MYSQL_DATABASE`.
MYSQL_PASSWORD: The password for `MYSQL_USER`. Defaults to a blank password.

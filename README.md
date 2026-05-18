# LAMP Stack Lab (Linux + Apache + MariaDB + PHP)

This project demonstrates a full LAMP stack setup on Ubuntu, simulating a basic web hosting environment.

It includes installation, configuration, and integration of Apache, PHP, and MariaDB, along with a working database connection test.

The project was created to practice Linux system administration, web server setup, and basic backend troubleshooting tasks similar to those performed in hosting support environments.

---

##  Technologies Used

- Ubuntu Linux
- Apache2 web server
- PHP 8+
- MariaDB
- MySQLi (PHP extension)

---

##  Features

- Apache web server configured and running
- PHP integration with Apache (mod_php)
- MariaDB database setup with user privileges
- PHP → Database connection test
- Systemd service management (apache2, mariadb)
- Basic troubleshooting of common LAMP issues

---

##  Project Screenshots

### Apache running web server
![Apache](screenshots/apache.png)

### Apache configuration check
![Apache Config](screenshots/apachecfg.png)

### PHP execution
![PHP](screenshots/php.png)

### MariaDB connection
![Database](screenshots/batabase.png)

### MySQL login
![MySQL](screenshots/mysql.png)

### Apache service status
![Systemctl](screenshots/systemctl-apache2.png)



##  Example Use Case

A simple PHP script connects to a MariaDB database and verifies connectivity:

Database connection test output:
> Database connected successfully 🎉

---

##  What I learned

- Linux server administration basics
- Apache configuration and service management
- SQL user and privilege management
- Debugging connection issues between PHP and database

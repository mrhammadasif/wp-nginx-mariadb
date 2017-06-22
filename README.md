## Docker Composer Configuration to Run Wordpress on Nginx with MariaDB

This is docker-composer configuration, which is based on

- Wordpress 4.8.0-fpm
- Nginx (1.13.1)
- MariaDB (10.3.0)


### Steps to start the Environment

1. Install docker from [docker website](https://www.docker.com/get-docker)
2. Clone this `repo`
3. Open your Terminal or CMD and browse to the **cloned repo**
4. Then run `docker-compose up -d`
5. Connect your MariaDB with using any SQL Client e.g. [Sequel Pro](https://www.sequelpro.com/download) localhost:3306 username=root password=root
6. Create Database with your desired name

### Install your WordPress with the following configuration

- DB Hostname **mariadb**
- DB Username **root**
- DB Password **root**
- DB Name **<NAME_OF_DATABASE>** 
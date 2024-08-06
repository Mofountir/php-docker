# php-docker demo 🐋🚀

Here is a simple demo to build a full stack web application in Php with a MySql database by running Docker containers.
It also chows how to modify the docker-compose.yml file to define the images and configuration settings needed to run your web app. 

⚠️ If you get the error: Fatal error: Uncaught Error: Call to undefined function mysqli_connect() in /var/www/html/index.php:3 Stack trace: #0 {main} thrown in /var/www/html/index.php on line 3

Open the interactive terminal with your docker container that's running the www service and run the command: docker-php-ext-install mysqli && docker-php-ext-enable mysqli && apachectl restart

### 📄 Documentation
- [Docker Documentation](https://docs.docker.com/) 🐳
- [PHP Documentation](https://www.php.net/docs.php) 🐘
- [MySQL Documentation](https://dev.mysql.com/doc/) 🐬
- [Docker Compose Documentation](https://docs.docker.com/compose/) 📦

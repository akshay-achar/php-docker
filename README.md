# php-docker
PHP Docker Setup


Steps:
1) Git clone 
2) Check if the docker is installed else then install sudo snap install docker  sudo apt  install docker.io   sudo apt  install docker-compose
3) Create a sample php file in project folder test.php 
3) In the php-docker folder run docker-compose up -d 
4) In the Browser, load the page http://localhost/test.php




Details: 
1) In Apache folder, apache-config.conf file is used to add the virtual host configurations.
2) In php/php.ini file is used to add the extension to enabled for the php version.
3) The files in the project folder will be added in the /var/www/html of the php  docker.



Useful Links:
1) https://docs.docker.com/compose/gettingstarted/
2) https://www.digitalocean.com/community/tutorials/how-to-install-docker-compose-on-ubuntu-16-04







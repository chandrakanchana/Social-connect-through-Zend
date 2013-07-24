<b>ZendApp</b>

ZendApp is built on Zend Framework and provides the social logins like facebook,twitter and google through Zend Framework


<b>INSTALLATION</b>

In ZendApp/application/config/application.ini set your database details

In ZendApp/public/includes/src/base_facebook.php 

please set the $currentUrl to you application url in getLoginUrl method

In ZendApp/application/controllers/IndexController.php

Please set your facebook,twitter and google auth keys and url's

<b>REQUIREMENTS</b>

You must have PHP 5.0 or greater installed

Mysql - 3.4.5

Zend version - 1.11

And you must set virtual host to set the paths

Setting Virtual host 

In your apache/config/httpd.conf file place the below lines

 <VirtualHost *:80>
   ServerName Zend Admin App
   DocumentRoot "your path to the ZendApp/public"     (Ex: C:/xampp/htdocs/ZendApp/public/)
   <Directory "your path to the ZendApp/public" >
   </Directory>
</VirtualHost>


<b>WHAT THIS APPLICATION CONSISTS </b>

Controllers<br/>
Models<br/>
Views<br/>

<b>SCREENSHOTS</b>

<img style="max-width:100%;" src="https://github.com/kanchana-nyros/Social-connect-through-Zend/raw/master/screenshots/ZendApp.png" alt="ZendApp" title="ZendApp">


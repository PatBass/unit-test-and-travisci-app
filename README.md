Unit test and Travis-ci use on a food diary app
===============================================

This application integrates an authentication with Github. You first need
 to create an OAuth application on the Github website : https://github.com/settings/applications/new.
 
 Once your OAuth application is created, you will need to get the `client ID` and
 `client secret` to put those information in the `app/config/parameters.yml` file.
 
Installation
============
 
First of all you need to run the `$ composer install`.
 
 This application requires a MySQL database. You need to configure the following parameters in the app/config/parameters.yml
 file :
 
     database_host
     database_port
     database_name
     database_user
     database_password
Then run the following commands in your favorite command line tool :

`$ bin/console doctrine:database:create`
`$ bin/console doctrine:schema:create`

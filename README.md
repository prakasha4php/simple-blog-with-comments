Simple blog implementation made on Symfony3 and AngularJs
====

Symfony3 is used as a REST api. AngularJs as a client.
Implemented nested comments and recaptcha.
Materialize is used as common CSS framework.

Instalation guide
-----------------
Install [Composer](http://getcomposer.org/) packages:

    composer install --dev

Install DB schema data:

    bin/console doctrine:schema:update --force

Load fixtures:

    bin/console doctrine:fixtures:load
    

Starting application (specify port hich you want):

    bin/console server:start 127.0.0.1:8080 --docroot ./public_html

    
For development, you should also install [Npm](https://www.npmjs.com/) packages (npm is used instead of Bower):

    npm install
    

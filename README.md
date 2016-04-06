Simple blog implementation made on Symfony3 and AngularJs
====

Symfony3 is used as REST api. AngularJs as client.
Implemented nested comments and recaptcha.
Materialize is used as common CSS framework.

Instalation guide
-----------------
Install composer pacjages:
  composer install --dev

Install DB tables:
  bin/console doctrine:schema:update --force

Load fixtures:
  bin/console doctrine:fixtures:load

# Madison PHP Conference 2018

Website for the 2018 Madison PHP Conference

## Installing

- Grab the project `git clone https://github.com/madisonphp/conference2018.git`
- Move into the project `cd conference2018`
- Install packages and dependencies `composer install`
- Configuration webserver
  - Apache/nginx:
    - Set `web/` as your public folder
  - PHP built-in web server
    - php -S localhost:8080 -t web web/index.php

## Deploy

- There is a webhook defined that should automatically update the site on pushes

## Resources

* [Bootstrap](http://getbootstrap.com/css/)
* [Twig](http://twig.sensiolabs.org/)
* [Silex](http://silex.sensiolabs.org/documentation)

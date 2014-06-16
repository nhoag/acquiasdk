# Acquia SDK for PHP
Sandbox for Acquia SDK for PHP module

The [Acquia SDK for PHP](https://github.com/acquia/acquia-sdk-php) allows
developers to build applications on top of Acquia services.

The Drupal module ensures that Acquia SDK for PHP is available to other modules.
You should not have to install it unless required by another module.

## Requirements
See individual branches for further details.

## Installation

Install the module to your *sites/all/modules* directory.

### With drush:

Run [Drush Composer](http://dgo.to/composer) install in the module directory:
```
    $ cd sites/all/modules/acquiasdk
    $ drush dl composer
    $ drush composer install
```

### Without drush:

Alternatively, if you don't have Drush installed:
```
    $ cd sites/all/modules/acquiasdk
    $ curl -s http://getcomposer.org/installer | php
    $ php composer.phar install
```


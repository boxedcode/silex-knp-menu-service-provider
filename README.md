# Silex Knp Menu Service Provider
This is a simple Silex Knp Menu Service Provider which is compatible with Silex 2.*. You can find out more about Knp Menu [here](https://github.com/KnpLabs/KnpMenu)

## Installation

Install using composer, more information on composer is available [here](https://getcomposer.org/). The following simple command will install `silex-knp-menu-service-provider` into your project, add a new entry in your composer.json file and update the composer.lock file as well.

    composer require boxedcode/silex-knp-menu-service-provider

## Usage

Simply register the service provider in your Silex 2.* application along the lines of the following:

    <?php 
    
    // Include dependencies installed with composer
    require 'vendor/autoload.php';
    
    use BoxedCode\Silex\Knp\MenuServiceProvider;
    use Silex\Application;
    
    $app = new Application();
    $app->register(new MenuServiceProvider());
    
## What now?

Follow the documentation available [here](https://github.com/KnpLabs/KnpMenu/blob/master/doc/01-Basic-Menus.markdown) and [here](https://github.com/KnpLabs/KnpMenu/blob/master/doc/02-Twig-Integration.markdown) to learn how to customise your menu and for other advanced usages of Knp Menu.

## Credits

Knp Menu is provided courtesy of the team over at [KnpLabs](http://www.knplabs.com/) and the Symfony Community. Silex is provided courtesy of the team over at [Sensio Labs](http://silex.sensiolabs.org/).
**this is the oab1 remix for php7**
* put tests in ../Tests, as is normal for Symfony
* include testee class in use statement
* message about test file written now correctly is hidden in case of failure
* added a few more safety rail exceptions
* edited test templates abit to match my style of unit tests
* added return type decl to method description

#TODO 
* patch Phar process as needed to make new binary

# PHPUnit Skeleton Generator

# LICENCE: 
The original project shipped under BSD3 clause licence.  I don't think I am allowed to change that to a different version of licence, so this project is my only BSD licenced software.

`phpunit-skelgen` is a tool that can generate skeleton test classes from production code classes and vice versa.

## Installation

### Composer

Simply add a dependency on `phpunit/phpunit-skeleton-generator` to your project's `composer.json` file if you use [Composer](http://getcomposer.org/) to manage the dependencies of your project. Here is a minimal example of a `composer.json` file that just defines a development-time dependency on phpunit/phpunit-skeleton-generator:

    {
        "require-dev": {
            "phpunit/phpunit-skeleton-generator": "*"
        }
    }

For a system-wide installation via Composer, you can run:

    composer global require "phpunit/phpunit-skeleton-generator=*"

Make sure you have `~/.composer/vendor/bin/` in your path.


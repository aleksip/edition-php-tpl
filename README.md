# Pattern Lab Edition for PHPTemplate

The Edition for PHPTemplate gives developers and designers a clean and stable base from which to develop a PHPTemplate-based pattern library.


## Packaged Components

The Edition for PHPTemplate comes with the following components:

* `pattern-lab/core`: [GitHub](https://github.com/pattern-lab/patternlab-php-core), [Packagist](https://packagist.org/packages/pattern-lab/core)
* `aleksip/patternengine-tpl`: [GitHub](https://github.com/aleksip/patternengine-php-tpl), [Packagist](https://packagist.org/packages/aleksip/patternengine-tpl)
* `pattern-lab/styleguidekit-assets-default`: [GitHub](https://github.com/pattern-lab/styleguidekit-assets-default), [Packagist](https://packagist.org/packages/pattern-lab/styleguidekit-assets-default)
* `aleksip/styleguidekit-tpl-default`: [GitHub](https://github.com/aleksip/styleguidekit-tpl-default), [Packagist](https://packagist.org/packages/aleksip/styleguidekit-tpl-default)


## Installing

Pattern Lab uses [Composer](https://getcomposer.org/) to manage project dependencies.


### 1. Install Composer

Please follow the directions for [installing Composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx) on the Composer website. We recommend you [install it globally](https://getcomposer.org/doc/00-intro.md#globally).


### 2. Install the Edition for PHPTemplate

Use Composer's [`create-project` command](https://getcomposer.org/doc/03-cli.md#create-project) to install the Edition for PHPTemplate into a location of your choosing. In Terminal type:

    cd install/location/
    composer create-project aleksip/edition-php-tpl your-project-name && cd $_

This will install the Edition for PHPTemplate into a directory called `your-project-name` in `install/location/`. During the set-up process you will be asked to install an appropriate StarterKit. You will be automatically dropped into the project directory after the process is finished.


## Updating Pattern Lab

To update Pattern Lab please refer to each component's GitHub repository. The components are listed at the top of the README.


## Helpful Commands

These are some helpful commands you can use on the command line for working with Pattern Lab.


### List all of the available commands

To list all available commands type:

    php core/console --help

To list the options for a particular command type:

    php core/console --help --[command]


### Generate Pattern Lab

To generate the front-end for Pattern Lab type:

    php core/console --generate


### Watch for changes and re-generate Pattern Lab

To watch for changes and re-generate the front-end for Pattern Lab type:

    php core/console --watch


### Start a server to view Pattern Lab

You can use PHP's built-in web server to review your Pattern Lab project in a browser. In a seperate window type:

    php core/console --server

Then open [http://localhost:8080](http://localhost:8080) in your browser.


### Install a StarterKit

To install a near-empty StarterKit as a starting point for your project type:

    php core/console --starterkit --init

To install a specific StarterKit from GitHub type:

    php core/console --starterkit --install <starterkit-vendor/starterkit-name>

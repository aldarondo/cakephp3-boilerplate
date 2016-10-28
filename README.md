# CakePHP3 Boilerplate

Based off of https://packagist.org/packages/cakephp/app

## Installation

1. Install PHP 5.5.9 (CLI) or higher
2. Download [Composer](http://getcomposer.org/doc/00-intro.md) or update `composer self-update`.

More information can be found at http://book.cakephp.org/3.0/en/installation.html

## Configuration

Read and edit `config/app.php` and setup the 'Datasources' and any other
configuration relevant for your application.

## Development Server

bin/cake server

By default, without any arguments provided, this will serve your application at http://localhost:8765/.

If you have something conflicting with localhost or port 8765, you can tell the CakePHP console to run the web server on a specific host and/or port utilizing the following arguments:

bin/cake server -H 192.168.13.37 -p 5673
This will serve your application at http://192.168.13.37:5673/.

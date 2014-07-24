PuPHPet SMPROC4
===============

My default LAMP development stack for SMPROC

Installation:
-------------

Download and install [VirtualBox](http://www.virtualbox.org/)

Download and install [vagrant](http://vagrantup.com/)

Go to the repository folder and launch the box

    $ cd [repo]
    $ vagrant up

What's inside:
--------------
* Deploy Target
    * CentOS 6.5 x64
* Server Packages
    * [MailCatcher](http://mailcatcher.me/) 
* Firewall Rules
* Webservers
    * Apache
* Languages
    * PHP
    * PHP Module
        * cli
        * intl
        * mcrypt
    * PEAR Modules
    * PECL Modules
        * APC
        * APCu
        * memcache
        * memcached
        * WinCache
        * pecl_http
* Databases
    * MySQL
    * MongoDB
    * PostgreSQL
    * Redis
    * SQLite
* Work Queues
    * [RabbitMQ](http://www.rabbitmq.com/tutorials/tutorial-one-php.html)
* Search Servers
    * [Elastic Search](https://github.com/elasticsearch/elasticsearch-php)
* Xdebug with Webgrind
* [Composer](http://getcomposer.org/)

* Node.js with following packages:
    * [LESS](http://lesscss.org)

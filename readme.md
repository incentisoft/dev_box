# Basic Vagrant Box Setup [![Build Status](https://travis-ci.org/dreboard/basic_box.svg?branch=master)](https://travis-ci.org/dreboard/basic_box)

Basic vagrant boxes in Ubuntu and Centos:

- ubuntu/trusty64
- [Apache]
- PHP[7]
- Phpmyadmin
- Composer

## Requirements
- [VirtualBox](http://www.virtualbox.org/wiki/Downloads)
- [Vagrant](http://www.vagrantup.com/downloads)

## PHP Modules
php7.0-fpm php7.0-common php7.0-opcache php7.0-phpdbg php7.0-mbstring php7.0-gd php7.0-imap php7.0-ldap php7.0-pgsql php7.0-pspell php7.0-recode php7.0-snmp php7.0-tidy php7.0-dev php7.0-intl php7.0-gd php7.0-curl php7.0-zip php7.0-xml php7.0-curl php7.0-json php7.0-mcrypt


### Laravel users (Ubuntu)
If you are having issues with migrating follow the steps below
 
To know the address which MySQL is bound to do the following:
- cat /etc/mysql/my.cnf | grep bind-address (Use this host)
- cd /var/www/site_name (Your site name)
- php artisan migrate
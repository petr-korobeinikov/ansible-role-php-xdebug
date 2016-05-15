[![Build Status](https://travis-ci.org/pkorobeinikov/ansible-role-php-xdebug.svg?branch=master)](https://travis-ci.org/pkorobeinikov/ansible-role-php-xdebug)

ansible-role-php-xdebug
=======================

PHP Xdebug installation.

Requirements
------------

None.

Role Variables
--------------

* `php_xdebug_version` is an php package version for xdebug.

Dependencies
------------

* `pkorobeinikov.php`

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: pkorobeinikov.php-xdebug
          php_xdebug_version: 7.0

        - role: pkorobeinikov.php-xdebug
          php_xdebug_version: 5.6

License
-------

BSD, MIT

Ansible Role: php-memcached
=========

Install memcached extension for PHP with igbinary support.

Requirements
------------

Written in Ansible 2.3.*. PECL must be installed.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

### php_igbinary_version

The version of igbinary to install.

Default is `2.0.5`.

### php_memcached_version

The version of memcached extension to install.

Default is `3.0.4`.

### php_pecl_executable

The pecl executable file.

Default is `pecl`.

Dependencies
------------

- juwai.common
- geerlingguy.php

Example Playbook
----------------

    - hosts: servers
        roles:
         - juwai.php-memcached

License
-------

MIT

Author Information
------------------

This role was created in 2018 by [Juwai Limited](http://www.juwai.com).

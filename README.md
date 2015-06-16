dotdeb
======

An ansible role to ensure dotdeb.org package repositories are configured.


Role Variables
--------------

*dotdeb_php_version* - which PHP-specific repository to add.  Possible values are:
    * 55 - for PHP 5.5
    * 56 - for PHP 5.6
    * 56zts - For PHP 5.6 with Zend Thread Safety

Any other value will result in only the main dotdeb.org repos (bin and src) to be added.

See [dotdeb.org](https://www.dotdeb.org/instructions/) for more info.

License
-------

MIT

Author Information
------------------

Tim Lieberman <tim@timdev.com>

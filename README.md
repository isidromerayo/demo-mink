Demo Mink
=========

http://mink.behat.org/

Install (composer install is required)
--------------------------------------

http://getcomposer.org/doc/00-intro.md#locally

$ composer(.phar) install

Use
---

Single feature

$ bin/behat features/search.feature

All features

$ bin/behat

Using Selenium RC, you need to launch service.

$ sh ./launch-selenium.sh


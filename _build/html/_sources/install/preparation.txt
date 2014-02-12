Preparing to install the LRC Drupal Template site
=================================================

There are a couple of different ways you can set up the LRC Drupal Template website.
Before you start though, you need a webserver ready to install onto. This might be a local
machine you are using for development, your existing live web server, or a virtual server
or shared web space rented from an Internet Service Provider. The webserver can run on any
operating system and must meet the following requirements:

* Support for PHP 5.2 or higher (5.3+ preferred)
* At least 64MB memory limit for PHP, 80MB+ preferred
* MySQL database version 5
* Support the cUrl extensions for PHP to allow it to communicate with the BRC Community
  Warehouse.
* A tool allowing you to access the MySQL database server such as PhpMyAdmin, MySQL Query 
  Browser or CPanel
  
If you are installing a local development server, then installing a web-server stack makes
the setup process relatively easy. Here are a few examples for your consideration:

**Windows**

* `WampServer <http://www.wampserver.com/en/>`_

**Mac**

* `MAMP <http://www.mamp.info/en/index.html>`_

**Any operating system**

* `XAMPP <http://www.apachefriends.org/en/xampp.html>`_

Before starting the installation process, you will need to create a MySQL database ready 
for Drupal to use. The installation documentation for **Instant Indicia** (which is a 
Drupal 6 product) cover the `steps you need to create the MySQL database  
<http://indicia-docs.readthedocs.org/en/latest/site-building/instant-indicia/installation.html#using-cpanel>`_.
Alternatively, any tutorial on installation of vanilla Drupal will explain the steps 
required, as the LRC Drupal Template has no special requirements of the MySQL setup.
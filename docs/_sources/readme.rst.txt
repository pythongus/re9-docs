Re9 - Reboot
============

A reboot of the Re9 project

Package Management Tool
-----------------------

``poetry 1.0.5``

Python Version
--------------

``3.8.2``

OS
~~

* MX Linux

* Linux 4.19.0-6-amd64 #1 SMP Debian 4.19.67-2+deb10u2 (2019-11-11) x86_64 GNU/Linux

Using PostgreSQL
~~~~~~~~~~~~~~~~

The Python module used for this application is

``psycopg2``

The hard dependency for installing this module is 

``libpq-dev``

installable using command

.. code-block:: bash

    sudo apt install libpq-dev


Environment Variables
---------------------
.. code-block:: python

    DATABASE = 'RE9_DATABASE'
    USER = 'RE9_USER'
    SERVER = 'RE9_SERVER'
    PASSWORD = 'RE9_PWD'

FIPE REST API
-------------

Main Web Page
~~~~~~~~~~~~~~

`FIPE API <http://fipeapi.appspot.com/>`_


Marcas
~~~~~~

* http://fipeapi.appspot.com/api/1/carros/marcas.json 

Tests
-----
The tests are being run with

.. code-block:: bash

    RE9_PWD=`cat .config` pytest 

``.config`` is a protected local file with the required password.

Notes
-----

`database/username/password hint: re9/re9/n-sword`

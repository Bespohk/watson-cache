.. Watson - Cache documentation master file, created by
   sphinx-quickstart on Fri Jan 17 14:49:48 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. role:: python(code)
   :language: python

Watson-Cache
============

A collection of cache storage mechanisms that act like a dict.

Currently supporting:

-  Memory
-  File
-  Memcache

Also contains a decorator that can be used within the
``watson-framework`` package.

Build Status
------------

+-----------+------------------+---------------------+
| Branch    | Status           | Coverage            |
+===========+==================+=====================+
| Master    | |Build StatusM|  | |Coverage Status|   |
+-----------+------------------+---------------------+
| Develop   | |Build StatusD|  |                     |
+-----------+------------------+---------------------+

|Pypi|

Dependencies
------------

-  watson-common
-  watson-di (for test coverage, and decorator usage)

Installation
------------

``pip install watson-cache``

Testing
-------

Watson can be tested with py.test. Simply activate your virtualenv and run :python:`python setup.py test`.

Contributing
------------

If you would like to contribute to Watson, please feel free to issue a
pull request via Github with the associated tests for your code. Your
name will be added to the AUTHORS file under contributors.

Table of Contents
-----------------

.. include:: toc.rst.inc

.. |Coverage Status| image:: https://coveralls.io/repos/bespohk/watson-cache/badge.png
   :target: https://coveralls.io/r/bespohk/watson-cache
.. |Build StatusD| image:: https://api.travis-ci.org/bespohk/watson-cache.png?branch=develop
   :target: https://travis-ci.org/bespohk/watson-cache
.. |Build StatusM| image:: https://api.travis-ci.org/bespohk/watson-cache.png?branch=master
   :target: https://travis-ci.org/bespohk/watson-cache
.. |Pypi| image:: https://pypip.in/v/watson-cache/badge.png
   :target: https://crate.io/packages/watson-cache/

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

|Build Status| |Coverage Status| |Version| |Downloads| |Licence|

Dependencies
------------

-  watson-common
-  watson-di (for test coverage, and decorator usage)
-  python3-memcached

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

.. |Build Status| image:: https://api.travis-ci.org/Bespohk/watson-cache.png?branch=master
   :target: https://travis-ci.org/Bespohk/watson-cache
.. |Coverage Status| image:: https://coveralls.io/repos/bespohk/watson-cache/badge.png
   :target: https://coveralls.io/r/bespohk/watson-cache
.. |Version| image:: https://pypip.in/v/watson-cache/badge.png
   :target: https://pypi.python.org/pypi/watson-cache/
.. |Downloads| image:: https://pypip.in/d/watson-cache/badge.png
   :target: https://pypi.python.org/pypi/watson-cache/
.. |Licence| image:: https://pypip.in/license/watson-cache/badge.png
   :target: https://pypi.python.org/pypi/watson-cache/

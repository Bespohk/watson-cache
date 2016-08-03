Watson-Cache
============

A collection of cache storage mechanisms that act like a dict.

Currently supporting:

-  Memory
-  File
-  Memcache

Also contains a decorator that can be used within the
``watson-framework`` package.

For full documentation please see `Read The
Docs <http://watson-cache.readthedocs.org/>`__.

Build Status
^^^^^^^^^^^^

|Build Status| |Coverage Status| |Version|

Installation
------------

``pip install watson-cache``

Dependencies
------------

-  watson-common
-  watson-di (for test coverage, and decorator usage)
-  python3-memcached

Todo
----

-  Add SqlAlchemy based storage
-  Add Redis based storage

.. |Build Status| image:: https://img.shields.io/travis/watsonpy/watson-cache.svg?maxAge=2592000
   :target: https://travis-ci.org/watsonpy/watson-cache
.. |Coverage Status| image:: https://img.shields.io/coveralls/watsonpy/watson-cache.svg?maxAge=2592000
   :target: https://coveralls.io/r/watsonpy/watson-cache
.. |Version| image:: https://img.shields.io/pypi/v/watson-cache.svg?maxAge=2592000
   :target: https://pypi.python.org/pypi/watson-cache/

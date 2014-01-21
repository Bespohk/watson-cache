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

|Build Status| |Coverage Status| |Pypi|

Installation
------------

``pip install watson-cache``

Dependencies
------------

-  watson-common
-  watson-di (for test coverage, and decorator usage)

Todo
----

-  Add SqlAlchemy based storage
-  Add Redis based storage

.. |Build Status| image:: https://api.travis-ci.org/bespohk/watson-cache.png?branch=master
   :target: https://travis-ci.org/bespohk/watson-cache
.. |Coverage Status| image:: https://coveralls.io/repos/bespohk/watson-cache/badge.png
   :target: https://coveralls.io/r/bespohk/watson-cache
.. |Pypi| image:: https://pypip.in/v/watson-cache/badge.png
   :target: https://crate.io/packages/watson-cache/

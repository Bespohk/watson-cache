# Watson-Cache

A collection of cache storage mechanisms that act like a dict.

Currently supporting:

- Memory
- File
- Memcache

Also contains a decorator that can be used within the `watson-framework` package.

For full documentation please see [Read The Docs](https://readthedocs.org/projects/watson-cache/).

#### Build Status

Branch | Status | Coverage
------------ | ------------- | -------------
Master | [![Build Status](https://api.travis-ci.org/bespohk/watson-cache.png?branch=master)](https://travis-ci.org/bespohk/watson-cache) | [![Coverage Status](https://coveralls.io/repos/bespohk/watson-cache/badge.png)](https://coveralls.io/r/bespohk/watson-cache)
Develop | [![Build Status](https://api.travis-ci.org/bespohk/watson-cache.png?branch=develop)](https://travis-ci.org/bespohk/watson-cache) |

[![Pypi](https://pypip.in/v/watson-cache/badge.png)](https://crate.io/packages/watson-cache/)

## Dependencies

* watson-common
* watson-di (for test coverage, and decorator usage)

## Todo

* Add SqlAlchemy based storage
* Add Redis based storage

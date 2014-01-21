Usage
=====

In order to use the Memcache backend, you must install ``python3-memcached`` first. This is available via ``pip install python3-memcached``.

.. code-block:: python

    cache = StorageType()
    cache['key'] = 'value'
    cache.set('key', 'value', timeout=360)
    cache['key']  # value
    cache.get('missing_key', default='value')  # value

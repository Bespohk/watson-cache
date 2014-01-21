Usage
=====

.. code-block:: python

    cache = StorageType()
    cache['key'] = 'value'
    cache.set('key', 'value', timeout=360)
    cache['key']  # value
    cache.get('missing_key', default='value')  # value

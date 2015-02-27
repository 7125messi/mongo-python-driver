`mongo_client` -- Tools for connecting to MongoDB
=================================================

.. automodule:: pymongo.mongo_client
   :synopsis: Tools for connecting to MongoDB

   .. autoclass:: pymongo.mongo_client.MongoClient(host='localhost', port=27017, max_pool_size=100, document_class=dict, tz_aware=False, **kwargs)

      .. automethod:: close

      .. describe:: c[db_name] || c.db_name

         Get the ``db_name`` `.Database` on `MongoClient` ``c``.

         Raises `~pymongo.errors.InvalidName` if an invalid database name is used.

      .. autoattribute:: host
      .. autoattribute:: port
      .. autoattribute:: is_primary
      .. autoattribute:: is_mongos
      .. autoattribute:: max_pool_size
      .. autoattribute:: nodes
      .. autoattribute:: document_class
      .. autoattribute:: tz_aware
      .. autoattribute:: max_bson_size
      .. autoattribute:: max_message_size
      .. autoattribute:: min_wire_version
      .. autoattribute:: max_wire_version
      .. autoattribute:: local_threshold_ms
      .. autoattribute:: codec_options
      .. autoattribute:: read_preference
      .. autoattribute:: write_concern
      .. autoattribute:: is_locked
      .. automethod:: database_names
      .. automethod:: drop_database
      .. automethod:: get_default_database
      .. automethod:: get_database
      .. automethod:: server_info
      .. automethod:: close_cursor
      .. automethod:: kill_cursors
      .. automethod:: set_cursor_manager
      .. automethod:: fsync
      .. automethod:: unlock

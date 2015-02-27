`mongo_replica_set_client` -- Tools for connecting to a MongoDB replica set
===========================================================================

.. automodule:: pymongo.mongo_replica_set_client
   :synopsis: Tools for connecting to a MongoDB replica set

   .. autoclass:: pymongo.mongo_replica_set_client.MongoReplicaSetClient(hosts_or_uri, max_pool_size=100, document_class=dict, tz_aware=False, **kwargs)

      .. automethod:: close

      .. describe:: c[db_name] || c.db_name

         Get the ``db_name`` `~pymongo.database.Database` on `MongoReplicaSetClient` ``c``.

         Raises `~pymongo.errors.InvalidName` if an invalid database name is used.

      .. autoattribute:: primary
      .. autoattribute:: secondaries
      .. autoattribute:: arbiters
      .. autoattribute:: is_mongos
      .. autoattribute:: max_pool_size
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
      .. automethod:: database_names
      .. automethod:: drop_database
      .. automethod:: get_default_database
      .. automethod:: close_cursor

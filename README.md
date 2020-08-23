# mongo-cluster-configsrv

Mongo cluster config service node.

This is meant to be used along with [http://github.com/stutzlab/mongo-cluster-router](mongo-cluster-router) and [http://github.com/stutzlab/mongo-cluster-shard](mongo-cluster-shard).

**Check http://github.com/stutzlab/mongo-cluster-shard for more details and examples.**

## ENVs

* CONFIG_REPLICA_SET - name of the replica set to be used in configsrv replication. defaults to 'configsrv'
* CONFIG_SERVER_NODES - command separated list of config servers. ex.: configsrv1,configsrv2,configsrv3. required
* SHARED_KEY_SECRET - secret name with shared key. defaults to '', which will run with no keyfile

## Volumes

* Mount volumes at "/data".

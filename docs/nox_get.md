## nox get

display a specific type of resource (index, document, etc.)

### Synopsis

display a specific type of resource (index, document, etc.)

### Options

```
  -h, --help   help for get
```

### Options inherited from parent commands

```
      --config string     config file (default is $HOME/nox.yaml)
  -d, --debug             toggle debug setting
  -H, --host string       host of your elasticsearch cluster (default "localhost")
  -W, --password string   password for authentication with the cluster
  -p, --port string       port for communication with your elasticsearch cluster (default "9200")
      --pretty            toggle pretty printing of returned json (default true)
      --silent            toggle silent output
  -t, --tls               use TLS for cluster connections
  -u, --username string   username for authentication with the cluster
```

### SEE ALSO

* [nox](nox.md)	 - Elasticsearch infrastructure management tool
* [nox get cluster](nox_get_cluster.md)	 - run cluster-level operations
* [nox get document](nox_get_document.md)	 - Get a document
* [nox get node](nox_get_node.md)	 - Show info for a specific node
* [nox get remote](nox_get_remote.md)	 - Run node-level operations
* [nox get snapshot](nox_get_snapshot.md)	 - Get details about a snapshot
* [nox get tasks](nox_get_tasks.md)	 - information about cluster tasks

###### Auto generated by spf13/cobra on 31-May-2019
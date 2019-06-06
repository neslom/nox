## nox list nodes stats

node stats

### Synopsis

The cluster nodes stats API allows to retrieve one or more (or all) of the cluster nodes statistics

```
nox list nodes stats [flags]
```

### Options

```
  -h, --help   help for stats
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

* [nox list nodes](nox_list_nodes.md)	 - List all nodes
* [nox list nodes stats search](nox_list_nodes_stats_search.md)	 - Get stats associated with search running on nodes

###### Auto generated by spf13/cobra on 31-May-2019
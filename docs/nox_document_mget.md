## nox document mget

Get multiple documents

### Synopsis

Multi GET API allows to get multiple
documents based on an index, type (optional) and
id (and possibly routing). The response includes a docs
array with all the fetched documents in order corresponding to the original
multi-get request (if there was a failure for a specific get,
an object containing this error is included in place in the response instead).
The structure of a successful get is similar in structure to a document provided by the get API.

```
nox document mget [index] [flags]
```

### Options

```
  -b, --body string     json body to send with this request
  -f, --fields string   comma separated list of fields to retrieve
  -h, --help            help for mget
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

* [nox document](nox_document.md)	 - tool for managing documents

###### Auto generated by spf13/cobra on 11-Jun-2019

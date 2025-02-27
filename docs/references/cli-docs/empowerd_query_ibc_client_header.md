## empowerd query ibc client header

Query the latest header of the running chain

### Synopsis

Query the latest Tendermint header of the running chain

```
empowerd query ibc client header [flags]
```

### Examples

```
empowerd query ibc client  header
```

### Options

```
      --grpc-addr string   the gRPC endpoint to use for this chain
      --grpc-insecure      allow gRPC over insecure channels, if not TLS the server must use TLS
      --height int         Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help               help for header
      --node string        \<host\>:\<port\> to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
  -o, --output string      Output format (text|json) (default "text")
```

### SEE ALSO

* [empowerd query ibc client](empowerd_query_ibc_client.md)	 - IBC client query subcommands


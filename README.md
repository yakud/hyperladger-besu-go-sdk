### Hyperladger-go-sdk
This repo is part of [go-ethereum](https://github.com/ethereum/go-ethereum) adapted for hyperladger-besu.
Client provides only requesting methods.

```
    url:= "ws://..." // node address 
    
    ctx:= context.Background()
	RPC, err := rpc.DialContext(ctx, url)
	if err != nil {
		log.Panicf("error connecting node: %s", err.Error())
	}
	client := ethclient.NewClient(RPC)
```

The repo is in WIP. Please pay attention. 
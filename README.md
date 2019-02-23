# ruimarinho/bitcoin-core

See Origin README [uimarinho/docker-bitcoin-core's README](https://github.com/ruimarinho/docker-bitcoin-core/blob/master/README.md)

## document

### start mining
```
$ docker exec --user bitcoin bitcoin-server bitcoin-cli generate 1
[
  "764e9777c9b9a2a5023759e64e2d51b98584eb90f501cfd3f336e1247e3863f8"
]
```

### get mininginfo
```
$docker exec --user bitcoin bitcoin-server bitcoin-cli getmininginfo
{
  "blocks": 102,
  "currentblockweight": 4000,
  "currentblocktx": 0,
  "difficulty": 4.656542373906925e-10,
  "networkhashps": 8.026730334062129e-07,
  "pooledtx": 0,
  "chain": "regtest",
  "warnings": ""
}
```
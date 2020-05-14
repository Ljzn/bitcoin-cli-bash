# Command Line Bitcoind RPC Client

set the rpc username and password in `rpc.conf`
```
machine localhost login [your username] password [your password]
```

example:
```
$ ./bitcoin-cli getinfo
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   691  100   620  100    71  29332   3359 --:--:-- --:--:-- --:--:-- 31000
{
   "id" : "curltest",
   "result" : {
      "maxstackmemoryusagepolicy" : 100000000,
      "blocks" : 133373,
      "protocolversion" : 70015,
      "connections" : 8,
      "paytxfee" : 0,
      "version" : 101000300,
      "errors" : "Warning: The network does not appear to fully agree! We received headers of a large fork. Still waiting for block data for more details.",
      "maxminedblocksize" : 128000000,
      "testnet" : false,
      "proxy" : "",
      "difficulty" : 1379192.28822808,
      "relayfee" : 2.5e-06,
      "keypoololdest" : 1589448536,
      "balance" : 0,
      "timeoffset" : 0,
      "stn" : false,
      "walletversion" : 160300,
      "keypoolsize" : 2000,
      "maxblocksize" : 2000000000,
      "maxstackmemoryusageconsensus" : 200000000
   },
   "error" : null
}
```

## contribute

Feel free to add the missing methonds via PR.
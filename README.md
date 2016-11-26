** Init

```
geth --datadir /home/gas/projects/ethereum/datadir init /home/gas/projects/ethereum/dev/genesis.json
```

** Run command line

```
geth --fast --cache 512 --ipcpath /home/gas/projects/ethereum/lib/geth.ipc --networkid 1234 --datadir /home/gas/projects/ethereum/datadir console 
```

** Run without command line

```
geth --fast --cache 512 --ipcpath /home/gas/projects/ethereum/lib/geth.ipc --networkid 1234 --datadir /home/gas/projects/ethereum/datadir --ipcapi "admin,db,eth,debug,miner,net,shh,txpool,personal,web3"
```

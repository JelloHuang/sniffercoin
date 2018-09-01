## How To Get Bitcoin Wallet Newaddress Linux Version
*  Download binary From [https://bitcoin.org/bin/](https://bitcoin.org/bin/)
* run:

```
 ./bitcoind -daemon
```

```
./bitcoin-cli getnewaddress
```

```
34KrxXpioP1jNjkHRuECkDsSzyecC7RYsW
```

```
./bitcoin-cli  dumpprivkey 34KrxXpioP1jNjkHRuECkDsSzyecC7RYsW
```

```
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

 * Now u can check the new address at [https://www.blockchain.com/btc/address/34KrxXpioP1jNjkHRuECkDsSzyecC7RYsW  ](https://www.blockchain.com/btc/address/34KrxXpioP1jNjkHRuECkDsSzyecC7RYsW  )
 and the private key:**xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx** ,and pls 
keep the private secrecy 

* Encrypt wallet

```
./bitcoin-cli encryptwallet mypassword
```

* Decrypt wallet in 360s

```
./bitcoin-cli walletpassphrase mypassword 360
```

* Backup wallet to local.**the wallet.dat file is the wallet file and keep safely**

```
./bitcoin-cli backupwallet ./
```

```
wallet.dat
```

ref:
[https://en.bitcoin.it/wiki/Original_Bitcoin_client/API_calls_list](https://en.bitcoin.it/wiki/Original_Bitcoin_client/API_calls_list)
# Move Faucet

Faucet contracts written in Move language.

Deployed at `0x43417434fd869edee76cca2a4d2301e528a1551b1d719b75c350c3c97d15b8b9` address in Aptos Testnet.

### Request funds using Aptos CLI

You can request the following coins each 12 hours: 

**To request BTC:**

```shell
aptos move run --function-id 0x43417434fd869edee76cca2a4d2301e528a1551b1d719b75c350c3c97d15b8b9::faucet::request --type-args 0x43417434fd869edee76cca2a4d2301e528a1551b1d719b75c350c3c97d15b8b9::coins::BTC --args address:43417434fd869edee76cca2a4d2301e528a1551b1d719b75c350c3c97d15b8b9
```

**To request USDT:**

```shell
aptos move run --function-id 0x43417434fd869edee76cca2a4d2301e528a1551b1d719b75c350c3c97d15b8b9::faucet::request --type-args 0x43417434fd869edee76cca2a4d2301e528a1551b1d719b75c350c3c97d15b8b9::coins::USDT --args address:43417434fd869edee76cca2a4d2301e528a1551b1d719b75c350c3c97d15b8b9
```



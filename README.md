

Block explorer for Gamersnestcoin, a CryptoNote based cryptocurrency.

#### Installation

1) It takes data from the daemon Gamersnestcoin. It should be accessible from the Internet. Run gamersnestcoin with open port as follows:
```bash
./gamersnestcoin --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=11898
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Note

Powered by Turtle Blockchain Explorer v. 1.0.0, partially based on Cryptonote-universal-pool and Karbowanec-Blockchain-Explorer.

The style was redesigned by ux33 @ kryptokrona.

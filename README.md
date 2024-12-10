LndHub
======

Wrapper for Lightning Ne/tls.cert`) into the root folder of LndHub.

LndHub expects LND's wallet to be unlocked, if not — it will attempt to unlock it with the password stored in `config.lnd.password`.
Please note that this feature is limited to Bitcoin, so you can't use it if you use any other cryptocurrency with LND (e.g., Litecoin

LndHub is available on Docker Hub as [`bluewalletorganization/lndhub`](https://hub.docker.com/r/bluewalletorganization/lndhub).
Please note that this requires a separate instance of redis and LND and optionally, bitcoind.
You can also view Umbrel's implementation using docker-compose [here](https://github.com/getumbrel/umbrel/blob/280c87f0f323666b1b0552aeb24f60df94d1e43c/apps/lndhub/docker-compose.yml).

### Reference client implementation

Can be used in ReactNative or Nodejs environment

* https://github.com/BlueWallet/BlueWallet/blob/master/class/wallets/lightning-custodian-wallet.js



### Tests

Acceptance tests are in https://github.com/BlueWallet/BlueWallet/blob/master/tests/integration/lightning-custodian-wallet.test.js

![image](https://user-images.githubusercontent.com/1913337/52418916-f30beb00-2ae6-11e9-9d63-17189dc1ae8c.png)



## Responsible disclosure

Found critical bugs/vulnerabilities? Please email them to bluewallet@bluewallet.io
Thanks!

![](https://flowchain.io/fb0/images/logo-text%40128.png)

Flowchain OS is a distributed ledger technology (DLT) for MediaTek LinkIt Smart 7688 IoT devices.

# Introduction

`flowchain-os-lks7688` is a distribution based on [flowchain-ledger](https://github.com/flowchain/flowchain-ledger), a blockchain for the IoT, to support MediaTek LinkIt Smart 7688 IoT devices. 

<img src="https://flowchain.co/static/img/7688.png" style="height: 280px;" />

# Features

* Use [flowchain-ledger](https://github.com/flowchain/flowchain-ledger) as the kernel
* Mining-based Proof-of-Stake (PoS)
* Run on MediaTek LinkIt Smart 7688 IoT devices
* A modified version of the original flowchain-ledger to use the Node 0.12 engine adopted by MediaTek LinkIt Smart 7688

# Install

* Please download the latest [flowchain OS distribution release](https://github.com/flowchain/flowchain-os-lks7688/releases/tag/v1.0.0)
* Copy the release file to your LinkIt Smart 7688, for example:
```
$ scp v1.0.0.zip root@mylinkit.local
```
* Uncompress the file:
```
# unzip v1.0.0.zip
```
* Run as a flowchain peer node:
```
# cd flowchain-os-lks7688
# node node.js
```

Please note that you don't have to run `npm install` since the distribution has already bundled all dependent npms.

## License

Copyright (C) 2018 Jollen. The source code is licensed under the MIT license found in the [LICENSE](LICENSE) file.

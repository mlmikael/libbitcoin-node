[![Build Status](https://travis-ci.org/libbitcoin/libbitcoin-node.svg?branch=master)](https://travis-ci.org/libbitcoin/libbitcoin-node)

[![Coverage Status](https://coveralls.io/repos/libbitcoin/libbitcoin-node/badge.svg)](https://coveralls.io/r/libbitcoin/libbitcoin-node)

# Libbitcoin Node

*Bitcoin full node based on libbitcoin-blockchain*

Note that you need g++ 4.8 or higher. For this reason Ubuntu 12.04 and older are not supported. Make sure you have installed [libbitcoin-blockchain](https://github.com/libbitcoin/libbitcoin-blockchain) beforehand according to its build instructions.

```sh
$ ./autogen.sh
$ ./configure
$ make
$ sudo make install
$ sudo ldconfig
```

libbitcoin-node is now installed in `/usr/local/`.

Currently the `bitcoin-node` console app is for demonstration purposes only. See [libbitcoin-server](https://github.com/libbitcoin/libbitcoin-server) for current full node functionality.

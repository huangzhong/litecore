Bitcore
=======

[![NPM Package](https://img.shields.io/npm/v/bitcore.svg?style=flat-square)](https://www.npmjs.org/package/bitcore)
[![Build Status](https://img.shields.io/travis/bitpay/bitcore.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore)
[![Coverage Status](https://img.shields.io/coveralls/bitpay/bitcore.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitcore)

[![Sauce Test Status](https://saucelabs.com/browser-matrix/maraoz.svg)](https://saucelabs.com/u/maraoz)

A pure and powerful JavaScript Bitcoin library.

## Principles

Bitcoin is a powerful new peer-to-peer platform for the next generation of financial technology. The decentralized nature of the Bitcoin network allows for highly resilient bitcoin infrastructure, and the developer community needs reliable, open-source tools to implement bitcoin apps and services.

## Get Started

```
npm install bitcore
```

Using it in Node.js:

```javascript
var bitcore = require('bitcore');

assert(bitcore.Address.isValid('126vMmY1fyznpZiFTTnty3cm1Rw8wuheev'));
var simpleTx = new bitcore.Transaction();
var simpleTx.from(unspent).to(address, amount);
simpleTx.sign(privateKey);
```

## Documentation

The complete docs are hosted here: [bitcore documentation](http://bitcore.io/guide/). There's also a [bitcore API reference](http://bitcore.io/api/) available generated from the JSDocs of the project, where you'll find low-level details on each bitcore utility.

[Read the Developer Guide](http://bitcore.io/guide/)

[Read the API Reference](http://bitcore.io/api/)

To get community assistance and ask for help with implementation questions, please use our [community forums](http://bitpaylabs.com/c/bitcore).

## Examples

* [Generate a random address](https://github.com/bitpay/bitcore/blob/master/docs/examples.md#generate-a-random-address)
* [Generate a address from a SHA256 hash](https://github.com/bitpay/bitcore/blob/master/docs/examples.md#generate-a-address-from-a-sha256-hash)
* [Import an address via WIF](https://github.com/bitpay/bitcore/blob/master/docs/examples.md#import-an-address-via-wif)
* [Create a Transaction](https://github.com/bitpay/bitcore/blob/master/docs/examples.md#create-a-transaction)
* [Sign a Bitcoin message](https://github.com/bitpay/bitcore/blob/master/docs/examples.md#sign-a-bitcoin-message)
* [Verify a Bitcoin message](https://github.com/bitpay/bitcore/blob/master/docs/examples.md#verify-a-bitcoin-message)
* [Create an OP RETURN transaction](https://github.com/bitpay/bitcore/blob/master/docs/examples.md#create-an-op-return-transaction)
* [Create a 2-of-3 multisig P2SH address](https://github.com/bitpay/bitcore/blob/master/docs/examples.md#create-a-2-of-3-multisig-p2sh-address)
* [Spend from a 2-of-2 multisig P2SH address](https://github.com/bitpay/bitcore/blob/master/docs/examples.md#spend-from-a-2-of-2-multisig-p2sh-address)


## Modules
This module provides bitcoin's core features. Other features and protocol extensions are built into separate modules. Here is a list of official bitcore modules:

Module | Version | Building | Coverage
-------|---------|----------|---------
[bitcore-payment-protocol](http://github.com/bitpay/bitcore-payment-protocol) | [![NPM Package](https://img.shields.io/npm/v/bitcore-payment-protocol.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-payment-protocol) | [![Build Status](https://img.shields.io/travis/bitpay/bitcore-payment-protocol.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore-payment-protocol) | [![Coverage Status](https://img.shields.io/coveralls/bitpay/bitcore-payment-protocol.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitcore-payment-protocol)
[bitcore-p2p](http://github.com/bitpay/bitcore-p2p) | [![NPM Package](https://img.shields.io/npm/v/bitcore-p2p.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-p2p) | [![Build Status](https://img.shields.io/travis/bitpay/bitcore-p2p.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore-p2p) | [![Coverage Status](https://img.shields.io/coveralls/bitpay/bitcore-p2p.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitcore-p2p?branch=master)
[bitcore-mnemonic](http://github.com/bitpay/bitcore-mnemonic) | [![NPM Package](https://img.shields.io/npm/v/bitcore-mnemonic.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-mnemonic) |  [![Build Status](https://img.shields.io/travis/bitpay/bitcore-mnemonic.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore-mnemonic) | [![Coverage Status](https://img.shields.io/coveralls/bitpay/bitcore-mnemonic.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitcore-mnemonic)
[bitcore-ecies](http://github.com/bitpay/bitcore-ecies) | [![NPM Package](https://img.shields.io/npm/v/bitcore-ecies.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-ecies) | [![Build Status](https://img.shields.io/travis/bitpay/bitcore-ecies.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore-ecies) | [![Coverage Status](https://img.shields.io/coveralls/bitpay/bitcore-ecies.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitcore-ecies)
[bitcore-channel](http://github.com/bitpay/bitcore-channel) | [![NPM Package](https://img.shields.io/npm/v/bitcore-channel.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-channel) | [![Build Status](https://img.shields.io/travis/bitpay/bitcore-channel.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore-channel) | [![Coverage Status](https://img.shields.io/coveralls/bitpay/bitcore-channel.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitcore-channel)
[bitcore-explorers](http://github.com/bitpay/bitcore-explorers) | [![NPM Package](https://img.shields.io/npm/v/bitcore-explorers.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-explorers) | [![Build Status](https://img.shields.io/travis/bitpay/bitcore-explorers.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore-explorers) | [![Coverage Status](https://img.shields.io/coveralls/bitpay/bitcore-explorers.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitcore-explorers)
[bitcore-message](http://github.com/bitpay/bitcore-message) | [![NPM Package](https://img.shields.io/npm/v/bitcore-message.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-message) | [![Build Status](https://img.shields.io/travis/bitpay/bitcore-message.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore-message) | [![Coverage Status](https://img.shields.io/coveralls/bitpay/bitcore-message.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitcore-message)

## Security

We're using Bitcore in production, as are [many others](http://bitcore.io#projects), but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.

If you find a security issue, please email security@bitpay.com.

## Contributing

Please send pull requests for bug fixes, code optimization, and ideas for improvement. For more information on how to contribute, please refer to our [CONTRIBUTING](https://github.com/bitpay/bitcore/blob/master/CONTRIBUTING.md) file. 

## Building the Browser Bundle

To build bitcore full bundle for the browser:

```sh
gulp browser
```

This will generate files named `bitcore.js` and `bitcore.min.js`.

You can also use our pre-generated files, provided for each release along with a PGP signature by one of the project's main contributors. To get them, checkout a release commit (for example, https://github.com/bitpay/bitcore/commit/2670cd1ac5ec1742aae0599e1583c063415959ff for v0.10.4).

To verify signatures, use the following PGP keys:
- @maraoz: https://pgp.mit.edu/pks/lookup?op=get&search=0x64F3727BFE0B3196
- @eordano: https://pgp.mit.edu/pks/lookup?op=get&search=0x00BD4BAF1DEEAC20
- @yemel: https://pgp.mit.edu/pks/lookup?op=get&search=0xB4A468A6F14B6843
- @braydonf: https://pgp.mit.edu/pks/lookup?op=get&search=0x9BBF07CAC07A276D

## Tests

Run all the tests:

```sh
gulp test
```

You can also run just the NodeJS tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

Code released under [the MIT license](https://github.com/bitpay/bitcore/blob/master/LICENSE).

Copyright 2013-2015 BitPay, Inc. Bitcore is a trademark maintained by BitPay, Inc.

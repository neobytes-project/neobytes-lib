Neobytescore Library
=======

[![NPM Package](https://img.shields.io/npm/v/neobytescore-lib.svg)](https://www.npmjs.org/package/neobytescore-lib)

A pure and powerful JavaScript Neobytes library.

## Principles

Neobytes is a powerful new peer-to-peer platform for the next generation of financial technology. The decentralized nature of the Neobytes network allows for highly resilient neobytes infrastructure, and the developer community needs reliable, open-source tools to implement neobytes apps and services.

## Get Started

```
npm install neobytescore-lib
```

```
bower install neobytescore-lib
```

## Documentation

The complete docs are hosted here: [bitcore documentation](http://bitcore.io/guide/). There's also a [bitcore API reference](http://bitcore.io/api/) available generated from the JSDocs of the project, where you'll find low-level details on each bitcore utility.

- [Read the Developer Guide](http://bitcore.io/guide/)
- [Read the API Reference](http://bitcore.io/api/)

To get community assistance and ask for help with implementation questions, please use our [community forums](https://forum.bitcore.io/).

## Examples

* [Generate a random address](https://github.com/neobytes-project/neobytescore-lib/blob/master/docs/examples.md#generate-a-random-address)
* [Generate a address from a SHA256 hash](https://github.com/neobytes-project/neobytescore-lib/blob/master/docs/examples.md#generate-a-address-from-a-sha256-hash)
* [Import an address via WIF](https://github.com/neobytes-project/neobytescore-lib/blob/master/docs/examples.md#import-an-address-via-wif)
* [Create a Transaction](https://github.com/neobytes-project/neobytescore-lib/blob/master/docs/examples.md#create-a-transaction)
* [Sign a Neobytes message](https://github.com/neobytes-project/neobytescore-lib/blob/master/docs/examples.md#sign-a-bitcoin-message)
* [Verify a Neobytes message](https://github.com/neobytes-project/neobytescore-lib/blob/master/docs/examples.md#verify-a-bitcoin-message)
* [Create an OP RETURN transaction](https://github.com/neobytes-project/neobytescore-lib/blob/master/docs/examples.md#create-an-op-return-transaction)
* [Create a 2-of-3 multisig P2SH address](https://github.com/neobytes-project/neobytescore-lib/blob/master/docs/examples.md#create-a-2-of-3-multisig-p2sh-address)
* [Spend from a 2-of-2 multisig P2SH address](https://github.com/neobytes-project/neobytescore-lib/blob/master/docs/examples.md#spend-from-a-2-of-2-multisig-p2sh-address)


## Security

We're using Bitcore in production, as are [many others](http://bitcore.io#projects), but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.

## Contributing

Please send pull requests for bug fixes, code optimization, and ideas for improvement. For more information on how to contribute, please refer to our [CONTRIBUTING](https://github.com/neobytes-project/neobytescore-lib/blob/master/CONTRIBUTING.md) file.

## Building the Browser Bundle

To build a neobytescore-lib full bundle for the browser:

```sh
gulp browser
```

This will generate files named `neobytescore-lib.js` and `neobytescore-lib.min.js`.

## Development & Tests

```sh
git clone https://github.com/neobytes-project/neobytescore-lib
cd neobytescore-lib
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

Code released under [the MIT license](https://github.com/neobytes-project/neobytescore-lib/blob/master/LICENSE).

Copyright 2013-2017 BitPay, Inc. Bitcore is a trademark maintained by BitPay, Inc.
Copyright 2016-2017 The Dash Foundation, Inc.

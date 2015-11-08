Gamecreditscore Library
=======

A pure and powerful JavaScript Bitcoin library.

## Principles

Bitcoin is a powerful new peer-to-peer platform for the next generation of financial technology. The decentralized nature of the Bitcoin network allows for highly resilient bitcoin infrastructure, and the developer community needs reliable, open-source tools to implement bitcoin apps and services.

## Get Started

```
npm install gamecreditscore-lib
```

```
bower install gamecreditscore-lib
```

## Documentation

The complete docs are hosted here: [gamecreditscore documentation](http://gamecreditscore.io/guide/). There's also a [gamecreditscore API reference](http://gamecreditscore.io/api/) available generated from the JSDocs of the project, where you'll find low-level details on each gamecreditscore utility.

- [Read the Developer Guide](http://gamecreditscore.io/guide/)
- [Read the API Reference](http://gamecreditscore.io/api/)

To get community assistance and ask for help with implementation questions, please use our [community forums](https://forum.gamecreditscore.io/).

## Examples

* [Generate a random address](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/docs/examples.md#generate-a-random-address)
* [Generate a address from a SHA256 hash](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/docs/examples.md#generate-a-address-from-a-sha256-hash)
* [Import an address via WIF](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/docs/examples.md#import-an-address-via-wif)
* [Create a Transaction](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/docs/examples.md#create-a-transaction)
* [Sign a Bitcoin message](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/docs/examples.md#sign-a-bitcoin-message)
* [Verify a Bitcoin message](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/docs/examples.md#verify-a-bitcoin-message)
* [Create an OP RETURN transaction](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/docs/examples.md#create-an-op-return-transaction)
* [Create a 2-of-3 multisig P2SH address](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/docs/examples.md#create-a-2-of-3-multisig-p2sh-address)
* [Spend from a 2-of-2 multisig P2SH address](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/docs/examples.md#spend-from-a-2-of-2-multisig-p2sh-address)


## Security

We're using Gamecreditscore in production, as are [many others](http://gamecreditscore.io#projects), but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.

If you find a security issue, please email security@Gamecredits-Universe.com.

## Contributing

Please send pull requests for bug fixes, code optimization, and ideas for improvement. For more information on how to contribute, please refer to our [CONTRIBUTING](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/CONTRIBUTING.md) file.

## Building the Browser Bundle

To build a gamecreditscore-lib full bundle for the browser:

```sh
gulp browser
```

This will generate files named `gamecreditscore-lib.js` and `gamecreditscore-lib.min.js`.

You can also use our pre-generated files, provided for each release along with a PGP signature by one of the project's maintainers. To get them, checkout a release commit (for example, https://github.com/Gamecredits-Universe/gamecreditscore-lib/commit/e33b6e3ba6a1e5830a079e02d949fce69ea33546 for v0.12.6).

To verify signatures, use the following PGP keys:
- @braydonf: https://pgp.mit.edu/pks/lookup?op=get&search=0x9BBF07CAC07A276D
- @pnagurny: https://pgp.mit.edu/pks/lookup?op=get&search=0x0909B33F0AA53013

## Development & Tests

```sh
git clone https://github.com/Gamecredits-Universe/gamecreditscore-lib
cd gamecreditscore-lib
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

Code released under [the MIT license](https://github.com/Gamecredits-Universe/gamecreditscore-lib/blob/master/LICENSE).

Copyright 2013-2015 Gamecredits-Universe, Inc. Gamecreditscore is a trademark maintained by Gamecredits-Universe, Inc.

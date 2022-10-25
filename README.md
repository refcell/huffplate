<img align="right" width="150" height="150" top="100" src="./assets/plate.png">

# huffplate • [![ci](https://github.com/abigger87/huffplate/actions/workflows/ci.yaml/badge.svg)](https://github.com/abigger87/huffplate/actions/workflows/ci.yaml) ![license](https://img.shields.io/github/license/abigger87/huffplate?label=license) ![solidity](https://img.shields.io/badge/solidity-^0.8.15-lightgrey) ![huff](https://img.shields.io/badge/huff-0.3.0-8b6c5c)

A **Robust**, **Extensible** Template for Huff Projects

> **Warning**
>
> These contracts are **unaudited** and are not recommended for use in production.
>
> Although contracts have been rigorously reviewed, this is **experimental software** and is provided on an "as is" and "as available" basis.
> We **do not give any warranties** and **will not be liable for any loss** incurred through any use of this codebase.


### Getting Started

Click [`use this template`](https://github.com/abigger87/huffplate/generate) to create a new repository with this repo as the initial state.

Or, if your repo already exists, run:
```sh
forge init --template https://github.com/abigger87/huffplate
git submodule update --init --recursive
forge install
```


### Blueprint

```txt
lib
├─ forge-std — https://github.com/foundry-rs/forge-std
├─ solmate — https://github.com/Rari-Capital/solmate
scripts
├─ Deploy.s.sol — Simple Deployment Script
src
├─ SimpleStore.sol — A Minimal Storage Contract
test
└─ SimpleStore.t.sol — SimpleStore Tests
```


### Development

Install dependencies, compile your contracts, and test all with [Foundry](https://github.com/foundry-rs/foundry)!

```bash
forge install
forge build
forge test
```


#### First time with Forge/Foundry?

See the official Foundry installation [instructions](https://github.com/foundry-rs/foundry/blob/master/README.md#installation).

Then, install the [foundry](https://github.com/foundry-rs/foundry) toolchain installer (`foundryup`) with:
```bash
curl -L https://foundry.paradigm.xyz | bash
```

Now that you've installed the `foundryup` binary,
anytime you need to get the latest `forge` or `cast` binaries,
you can run `foundryup`.

So, simply execute:
```bash
foundryup
```

🎉 Foundry is installed! 🎉


#### Configure Foundry

Using [foundry.toml](./foundry.toml), Foundry is easily configurable.

For a full list of configuration options, see the Foundry [configuration documentation](https://github.com/foundry-rs/foundry/blob/master/config/README.md#all-options).


### License

[MIT](https://github.com/abigger87/huffplate/blob/master/LICENSE)


### Acknowledgements

- [femplate](https://github.com/abigger87/femplate)
- [foundry](https://github.com/foundry-rs/foundry)
- [solmate](https://github.com/Rari-Capital/solmate)
- [forge-std](https://github.com/brockelmore/forge-std)
- [forge-template](https://github.com/foundry-rs/forge-template)
- [foundry-toolchain](https://github.com/foundry-rs/foundry-toolchain)


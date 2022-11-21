# wallet-generator

![crates.io](https://img.shields.io/crates/v/walletgen.svg)

Generator of addresses and mnemonic phrases for blockchains

## Install

If you have Rust: `cargo install walletgen`

If you have Debian/Ubuntu: [Releases](https://github.com/CipherDogs/wallet-generator/releases)

## Usage

```bash
walletgen 1.1.0
DEADBLACKCLOVER <deadblackclover@protonmail.com>
Generator of addresses and mnemonic phrases for blockchains

USAGE:
    walletgen [OPTIONS] [SUBCOMMAND]

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -c, --count <INT>    Sets a address generate count

SUBCOMMANDS:
    bitcoin     Bitcoin blockchain
    cyber       cyber blockchain
    ethereum    Ethereum blockchain
    help        Prints this message or the help of the given subcommand(s)
    kusama      Kusama blockchain
    monero      Monero blockchain
    polkadot    Polkadot blockchain
```

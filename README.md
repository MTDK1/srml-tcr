[![Build Status](https://travis-ci.org/MTDK1/srml-tcr.svg?branch=master)](https://travis-ci.org/MTDK1/srml-tcr)

# Substrate Runtime Module
## TCR モジュール

[substrate-developer-hub/substrate-tcr](https://github.com/substrate-developer-hub/substrate-tcr) を [paritytech/substrte](https://github.com/paritytech/substrate/tree/6dc833c42ebb89a2684ed04be4689164eb59ca97) masterブランチにある runtime で利用できるように修正し、tcr と token モジュールを SRML として利用できるようにしたものです。

Cargo.toml（抜粋)
```
rstd = { package = "sr-std", git = 'https://github.com/paritytech/substrate.git', rev = '6dc833c42ebb89a2684ed04be4689164eb59ca97', default_features = false }
```

paritytech/substrate の rev は 6dc833c42ebb89a2684ed04be4689164eb59ca97 を指定しています。
Runtime でも同じ rev を指定する必要があります。


## Sample

このモジュールを利用しているサンプル

[MTDK1/node-template](https://github.com/MTDK1/node-template/tree/tcr) tcr ブランチ
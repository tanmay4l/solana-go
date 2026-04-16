# Changelog

## [1.18.0](https://github.com/solana-foundation/solana-go/compare/v1.17.0...v1.18.0) (2026-04-16)


### Features

* add getters to txn with meta ([48d196b](https://github.com/solana-foundation/solana-go/commit/48d196b47f79212bd4e97fb61d35b0482b5ef8e9))
* add token-2022 extensions ([04dfc79](https://github.com/solana-foundation/solana-go/commit/04dfc794b4061522954fa3f10f5bfad2ff982728))
* add token-2022 extensions ([db2fdaa](https://github.com/solana-foundation/solana-go/commit/db2fdaa42ed9062d23eb51ae278856197fb66633))
* stake state types & ext tests ([6325515](https://github.com/solana-foundation/solana-go/commit/6325515ae6686d10351a1649e3b46951811e1fbe))
* stake state types & ext tests ([ea77e31](https://github.com/solana-foundation/solana-go/commit/ea77e318bb8158f391b349dd6c736fc457dbda46))
* vote program complete ([173d7f4](https://github.com/solana-foundation/solana-go/commit/173d7f4059fd12e5d747d5b0ffea7850211086a2))
* vote program complete ([dcff584](https://github.com/solana-foundation/solana-go/commit/dcff5845b15ca32c90a9b4336e8a902917132854))


### Bug Fixes

* allign rpc client with agave ([49bc8d6](https://github.com/solana-foundation/solana-go/commit/49bc8d6c44e53b9ab8710c8c333e479514678e40))
* allign rpc client with agave ([c985b99](https://github.com/solana-foundation/solana-go/commit/c985b99fd333a46eaacd8b5dfab2db697bdab54c))
* memo program parity ([f832bd8](https://github.com/solana-foundation/solana-go/commit/f832bd84b73eb5a3f2222072d45a8d8c5efeac56))
* memo program parity ([7550777](https://github.com/solana-foundation/solana-go/commit/755077780d34ed78d3a8c00a9e7d54542e66d051))


### Performance Improvements

* **message:** eliminate complex scans, struct copies, and redundant allocs ([aea7d1f](https://github.com/solana-foundation/solana-go/commit/aea7d1f61da18b240d741fb003e83182c968e701))
* **message:** eliminate complex scans, struct copies, and redundant allocs ([adbb10e](https://github.com/solana-foundation/solana-go/commit/adbb10e200c3979dafdee38fb2e13dbe356ab58d))

## Change log

The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this
project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html). See
[MAINTAINERS.md](./MAINTAINERS.md) for instructions to keep up to
date.

```
⚠️ solana-go works using SemVer but in 0 version, which means that the 'minor' will be changed when some broken changes are introduced into the application, and the 'patch' will be changed when a new feature with new changes is added or for bug fixing. As soon as v1.0.0 be released, solana-go will start to use SemVer as usual.
```

## [v0.1.0] 2020-11-09

First release

## Includes the following features:

* Get basic information from the chain about accounts, balances, etc.
* Issue SOL native token transfer
* Issue SPL token transfers
* Get Project SERUM markets list and live market data

## [1.3.3](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.3.2...v1.3.3) (2022-01-26)


### Bug Fixes

* correct ssl settings in db sealed secret ([7056c2f](https://github.com/Greenstand/bulk-pack-consumer/commit/7056c2f6633fe847aecaa82b09c7f15eed118080))

## [1.3.2](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.3.1...v1.3.2) (2022-01-06)


### Bug Fixes

* upgrade pg module ([ca31f10](https://github.com/Greenstand/bulk-pack-consumer/commit/ca31f10556e78a554d0d8d5b768c4e19c05c2242))

## [1.3.1](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.3.0...v1.3.1) (2021-12-08)


### Bug Fixes

* reseal the database secret with correct ssl settings ([6ff3a97](https://github.com/Greenstand/bulk-pack-consumer/commit/6ff3a977079b32b837f937a7edc80361fab3f270))
* update bulk pack database connection secret ([36e1401](https://github.com/Greenstand/bulk-pack-consumer/commit/36e1401ea3bcd6d5baeb06ee212a16080ecfed31))

# [1.3.0](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.2.0...v1.3.0) (2021-11-09)


### Features

* upgrade to node 16 ([94d5167](https://github.com/Greenstand/bulk-pack-consumer/commit/94d516749e6c7d47683d0f110f1e89bab2716696))

# [1.2.0](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.1.2...v1.2.0) (2021-10-20)


### Features

* move deployment to microservices-node-pool ([1972b78](https://github.com/Greenstand/bulk-pack-consumer/commit/1972b7887053df9ff2dd8c8c6773b1d348e5771e))

## [1.1.2](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.1.1...v1.1.2) (2021-10-14)


### Bug Fixes

* update production bulk pack database connection ([cc58bf7](https://github.com/Greenstand/bulk-pack-consumer/commit/cc58bf7f26399b504375d8e39f6672efa7358154))

## [1.1.1](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.1.0...v1.1.1) (2021-10-14)


### Bug Fixes

* revert fix: correct sqs url ([f82f107](https://github.com/Greenstand/bulk-pack-consumer/commit/f82f107af6106fe8906bcd8f09f02970f899df67))

# [1.1.0](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.16...v1.1.0) (2021-10-14)


### Bug Fixes

* added deployment details for production ([896eb82](https://github.com/Greenstand/bulk-pack-consumer/commit/896eb8232c86cb92c32caf9ba1462dd12dab0713))
* correct sqs url ([a6c4adf](https://github.com/Greenstand/bulk-pack-consumer/commit/a6c4adf2cfc8dd6a693d4f9b987887e13a911b44))


### Features

* upgrade to node 14 ([313367f](https://github.com/Greenstand/bulk-pack-consumer/commit/313367f34ce505ceb7e7fd28e94c63dfb5e7cafc))

## [1.0.16](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.15...v1.0.16) (2021-07-27)


### Bug Fixes

* correct database connection for test ([d98e643](https://github.com/Greenstand/bulk-pack-consumer/commit/d98e643541be9d8586728fdd9f9a2d078c5ab2f0))

## [1.0.15](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.14...v1.0.15) (2021-07-27)


### Bug Fixes

* add correct resources for test deployment ([ec38b55](https://github.com/Greenstand/bulk-pack-consumer/commit/ec38b55a7cb80d7dfbaf4871e34fe31e50ba1a76))
* scale to 2 replicas in test ([878e69d](https://github.com/Greenstand/bulk-pack-consumer/commit/878e69d7a66607cd964a36b86c3a2bdf0030da6b))

## [1.0.14](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.13...v1.0.14) (2021-07-27)


### Bug Fixes

* fix resource names, use defaults ([bf50588](https://github.com/Greenstand/bulk-pack-consumer/commit/bf505882831ea744e545cae15e406cbf51fa34e8))

## [1.0.13](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.12...v1.0.13) (2021-07-27)


### Bug Fixes

* fix resource names ([f683b32](https://github.com/Greenstand/bulk-pack-consumer/commit/f683b321da2dd23b588b24423f422a709b7d8fd9))

## [1.0.12](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.11...v1.0.12) (2021-07-27)


### Bug Fixes

* fix resource names to be standard ([be1eaba](https://github.com/Greenstand/bulk-pack-consumer/commit/be1eabade9aec4242b1af31b56e625f851ebf677))

## [1.0.11](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.10...v1.0.11) (2021-07-27)


### Bug Fixes

* recreate sealed secret ([9740321](https://github.com/Greenstand/bulk-pack-consumer/commit/97403212b951ca80ec7e7f872ae8c60d16ac4acc))

## [1.0.10](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.9...v1.0.10) (2021-07-27)


### Bug Fixes

* change to default resource names ([72910b9](https://github.com/Greenstand/bulk-pack-consumer/commit/72910b9016f1c4f31b1ec0a044696fe760e37cf1))
* change to default resource names ([c892021](https://github.com/Greenstand/bulk-pack-consumer/commit/c892021d273d96dbd0e0a99537444bf7b75e1d5b))

## [1.0.9](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.8...v1.0.9) (2021-07-21)


### Bug Fixes

* sqs url secret ([84bb4aa](https://github.com/Greenstand/bulk-pack-consumer/commit/84bb4aa2f776501d9c3ad310840c796beb055ae2))
* sqs url secret ([e00252c](https://github.com/Greenstand/bulk-pack-consumer/commit/e00252c89ea24f549f82e35925ae65faa86fd6a7))

## [1.0.8](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.7...v1.0.8) (2021-07-21)


### Bug Fixes

* database and aws key seal secrets ([4375e92](https://github.com/Greenstand/bulk-pack-consumer/commit/4375e92227ce8d08ffd88f17f90ede751c9ace68))
* wrong resource names ([6a9a423](https://github.com/Greenstand/bulk-pack-consumer/commit/6a9a423785dc8b486201d80643d0740bd4da1197))

## [1.0.7](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.6...v1.0.7) (2021-07-20)


### Bug Fixes

* reseal aws key id for test env ([0c419e4](https://github.com/Greenstand/bulk-pack-consumer/commit/0c419e43666e7cb4fb610b5a64871f9caf612446))

## [1.0.6](https://github.com/Greenstand/bulk-pack-consumer/compare/v1.0.5...v1.0.6) (2021-07-20)


### Bug Fixes

* add CI/CD configuration files ([1c6fdbb](https://github.com/Greenstand/bulk-pack-consumer/commit/1c6fdbbf5fab71aecddd0355cd9c563511c7963b))

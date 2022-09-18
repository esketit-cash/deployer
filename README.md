# Deployer [![Build Status](https://github.com/esketit-cash/deployer/workflows/build/badge.svg)](https://github.com/esketit-cash/deployer/actions)

A wrapper around EIP-2470 deployer that emits events with deployed contract address, or reverts on deploy failure. Contracts are deployed via underlying singleton factory, so expected addresses should be computed using singleton factory address and not deployer address.

## Dependencies

1. node 12
2. yarn

## Start

```bash
$ yarn
$ yarn test
```

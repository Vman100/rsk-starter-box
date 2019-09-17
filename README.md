# RSK Starter Box

## Description

This box provides basic elements to develop smart contracts for RSK Network.

This box comes with everything you need to start using smart contracts at RSK Network. It includes network configs for Mainnet and Testnet.

## Installation

First ensure you are in a new and empty directory and have truffle installed. 

If you don't have truffle installed you'll need to run this in order to install it.

```bash
npm install -g truffle
```

### Unboxing

Run the unbox command

```bash
truffle unbox rsk-starter-box
```

## Using the truffle console

You can start a truffle console for any RSK network

```bash
# Console for Mainnet
truffle console --network mainnet

# Console forn Testnet
truffle console --network testnet
```

## Migrating contracts

In order to migrate contracts to a specific network

```bash
# Migrate for Mainnet
truffle migrate --network mainnet

# Migrate for Testnet
truffle migrate --network testnet
```
# Uniswap V3 API Implementation <img src=".docs/logo.png" width=30/>

Implementation from Uniswap V3 guides for [contracts](https://docs.uniswap.org/protocol/guides/local-environment) (without SDK)

### Smart Contract Operations

- Liquidity Mining
- Swap (single, multihop)
- Providing Liquidity (mint new position, collecting fees, dec/inc liquidity)
- Flash Swaps

### Setup

```
yarn install
yarn dev
```

### Usage

Hardhat commands:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

# Ethereum NFTs

## Overview

- Based on [How to Create an NFT](https://docs.alchemyapi.io/alchemy/tutorials/how-to-write-and-deploy-an-nft).

## Prerequisites

The following prerequisites are required to be installed on your system:

- NodeJS 12
- Yarn (optional)
- [Alchemy](https://www.alchemyapi.io/)
- [Pinata](https://pinata.cloud/)
- Metamask

Then run:

```sh
yarn install
```

Get more ETH for testing: [link](http://rinkeby-faucet.com/)

Rinkeby Testnet Explorer: [link](https://rinkeby.etherscan.io/)

## Execution

### Compile smart contract

```sh
yarn run compile
```

### Deploy to rinkeby testnet network

```sh
yarn run deploy
```

### Mint an NFT

Firstly, update files: nft-metadata.json and src/mint-nft.js.

Then run:

```sh
yarn run mint
```

## Contribution

Your contribution is welcome and greatly appreciated. Please contribute your fixes and new features via a pull request.
Pull requests and proposed changes will then go through a code review and once approved will be merged into the project.

If you like my work, please leave me a star :)

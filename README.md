# Hardhat Project with TypeScript

This project demonstrates a basic Hardhat use case using typescript. It comes with a sample contract and a test for that contract. It is configured to work with `hardhat-deploy` plugin for intuitive contract deployment. And, `hardhat-etherscan` for contract verification. Beyond those the project also comes with example script and tasks.

Try running some of the following tasks:

Start with installing dependencies

```shell
yarn install
```

Then, start local hardhat chain

```shell
yarn chain
```

Run the test or compile and deploy

```shell
yarn test
yarn build
yarn deploy
```

Generate and show account

```shell
yarn generate
yarn account
```

Deploy to testnet and verify

```shell
yarn deploy --network rinkeby
yarn verify --network rinkeby DEPLOYED_CONTRACT_ADDRESS "Constructor argument 1"
```

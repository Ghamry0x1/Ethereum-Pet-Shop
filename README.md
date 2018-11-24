# Ethereum Pet Shop

## Ganache

Run Ganache

> ganache-cli

## Compilation

In a terminal, make sure you are in the root of the directory that contains the dapp and type:

> truffle compile

## Migration

Migrate the contract to the blockchain.

> truffle migrate

## Running the tests

Run the tests:

> truffle test

## Metamask

### Connect MetaMask to the blockchain created by Ganache.

-   Click the menu that shows "Main Network" and select Custom RPC

-   In the box titled "New RPC URL" enter http://127.0.0.1:8545 and click Save.

### Import Account

-   Import one of ganache accounts into metamask using its private key.

## Start local web server

> npm run dev

The dev server will launch and automatically open a new browser tab containing your dapp.

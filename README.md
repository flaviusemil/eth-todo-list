# Eth Todo List - A todo list build on the etherium blockchain.

> Note: This project isn't deployed on the live blockchain! It's a learning project.

## Install the required dev tools

For this demo you need the following browser extensions `MetaMask` and `MetaMask Legacy Web3`.

1. Install the required browser extensions
2. Install `Ganache`
3. In project run `npm install`
4. Install `truffle`
```bash
npm install truffle@5.0.2
```

## Setup the project

1. Start Ganache
2. In `MetaMask` connect to the local network blockchain on port `7545`
3. Import the first account into the `Metamask`

## Build and Deploy the smart contract

To build the project just run the following command
```bash
truffle build
```

To build and deploy the contract to the blockchain run:
```bash
truffle migrate --reset
```

## Run the tests
To run the tests just run the truffle test job.
```bash
truffle test
```

## Run the app
To run the app just run:
```bash
npm run dev
```

Now you can access the app on the `localhost:3000` by default.
If the port `3000` is used it will pick another port so check the logs.

When you open the app, a popup should appear asking you select your etherium account to use in the app.
Select the one you added it in the step #3 of the Setup project.

Done! Enjoy the demo!

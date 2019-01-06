# Setting up the development environment
There are a few technical requirements before we start. Please install the following:

- Node.js v6+ LTS and npm (comes with Node)
- Git

### Once we have those installed, we only need one command to install Truffle:

    npm install -g truffle

o verify that Truffle is installed properly, type truffle version on a terminal. If you see an error, make sure that your npm modules are added to your path.

We also will be using Ganache, a personal blockchain for Ethereum development you can use to deploy contracts, develop applications, and run tests. You can download Ganache by navigating to http://truffleframework.com/ganache and clicking the "Download" button.

### Back in our terminal, migrate the contract to the blockchain.

    truffle migrate

# Running the tests
### Back in the terminal, run the tests:

    truffle test

# Using the dapp
### Start the local web server:

    npm run dev
# Module-4-Project

The DegenToken contract is an ERC20 token smart contract that facilitates a Rewards system for players in the Degen Gaming platform. It allows the platform owner to create and distribute new tokens as rewards, enables players to transfer tokens to others, redeem tokens for in-game items, and check their token balance. Additionally, token holders can burn their tokens, and the platform owner has the authority to ban or unban accounts based on their behavior.

## Deployment

To create an Avalanche project and deploy a smart contract, follow these steps:

Open a command prompt and create a directory named "avalanche-project" with the command: $ mkdir avalanche-project.

Change into the "avalanche-project" directory using: $ cd avalanche-project.

Generate a new package.json file using: $ npm init -y.

Install the Hardhat development environment as a dev dependency: $ npm install --save-dev hardhat.

Create a JavaScript project by running: $ npx hardhat.

Install the Hardhat Toolbox plugin: $ npm i --save-dev @nomicfoundation/hardhat-toolbox.

Install the OpenZeppelin Contracts library as a dependency: $ npm install @openzeppelin/contracts.

Edit the hardhat.config.js file with the provided code, and also add your Snowtrace API key.

Update the deploy.js file located in the scripts folder with the provided code.

Set up the Avalanche network in your Metamask using the details provided (Network Name: Avalanche Fuji C-Chain, New RPC URL: https://api.avax-test.network/ext/bc/C/rpc, ChainID: 43113, Symbol: AVAX, Explorer: https://testnet.snowtrace.io/).

Request 2 AVAX from the Avalanche Testnet Faucet website to your Metamask wallet account for the contract to run.

Deploy the contract to the Fuji network using: $ npx hardhat run scripts/deploy.js --network fuji.

Verify the deployed smart contract address using: $ npx hardhat verify (INSERT CONTRACT ADDRESS) --network fuji.

Copy the Degen.sol contract and paste on the Remix Ethereum website.

In the deployment tab of Remix Ethereum, find the "At Address" tab and paste the contract address.

Now you can interact with the smart contract


## Author

Christian Baje

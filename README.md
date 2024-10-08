# AMANTOKEN Smart Contract

A smart contract is written to create a token on local hardhat network and interact with the smart contract using remix IDE
## Overview
The AMANTOKEN smart contract is an ERC20 token implementation using OpenZeppelin's ERC20 library. This contract allows the owner to mint tokens and any token holder to burn their own tokens. The token is named "AMANTOKEN" with the symbol "AMT".
## Description
For this project, you will write a smart contract to create your own token on a local HardHat network. Once you have your contract, you should be able to use remix to interact with it. From remix, the contract owner should be able to mint tokens to a provided address. Any user should be able to burn and transfer tokens.

Deployment on Local Hardhat Network
Follow these steps to deploy token on local hardhat network using local pc (here i have used VS Code)

Clone the repository and install its dependencies:
git clone
cd 
npm install
Install the @remix-project/remixd dependency to connect Remix IDE:
npm install -g @remix-project/remixd
Run the following command in the terminal to connect Remix IDE to the Hardhat local host:
remixd -s ./ --remix-ide https://remix.ethereum.org
Open a new terminal and start Hardhat's testing network:
npx hardhat node
Open the Remix online IDE in your browser.

Go to File Explorer -> Workspaces -> Connect to locahost and click confirm.

Rewrite the Token.sol file in the contracts directory with your own token code.

Compile the contract in the Remix IDE.

In the deploy section of Remix, select the environment as "Dev-Hardhat Provider".

Deploy your contract on the local Hardhat network using the deploy button in Remix.

Confirm the deployment transaction in Remix.

Once the contract is deployed, you will see the contract address in the Remix console. Make note of this address for future interactions.

Interacting with the Contract using Remix with Hardhat Provider
-After the contract is deployed, Remix will display the deployed contract instance in the "Deployed Contracts" section.

-Expand the deployed contract instance to see the available functions and their input fields.

-You can now interact with the contract by calling its functions and providing the required inputs.

-To mint tokens, call the mint function and provide the receiver's address and the desired amount. -To burn tokens, call the burn function and provide the amount to be burned.
## Authors
Aman patel

## License
This project is licensed under the MIT License - see the LICENSE.md file for details

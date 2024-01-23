# reimagined-guacamole
## Overview
This project demonstrates the integration of Web3.js with a Solidity smart contract. The smart contract, named CustomToken, is an ERC-20 token with additional functionalities to capture the latest transfer details such as timestamp, sender, and receiver.
 ## Table of Contents
 - [Overview](#overview)
 - [Table of Contents](#table of contents)
 - [Usage](#usage)
 - [Features](#features)
 ## Usage
# Environment Setup
1)Install Node.js and npm.
2)Install web3.js (npm install web3)
3)Configure web3.js to connect to your local blockchain (Ganache) or any public testnet.
# Deploy Smart Contract
1)Deploy the CustomToken smart contract to your chosen network(npx hardhat run deploy.js --network ganache).
# Run Web3.js Script
1)Run the Web3.js script to interact with the deployed smart contract(node web3-interaction.js)

## Features
- CustomToken Smart Contract: The smart contract is an ERC-20 token with added features to capture the timestamp, sender, and receiver of the latest transfer.
- Web3.js Integration: The project demonstrates how to use Web3.js to interact with Ethereum smart contracts.
- Latest Transfer Details: The script retrieves and prints the latest transfer details from the deployed smart contract.

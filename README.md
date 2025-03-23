# My ERC20 Token

## Overview

This repository contains the implementation of an ERC20 token smart contract deployed on the Sepolia test network. The token adheres to the ERC20 standard and provides functionalities such as transferring tokens, approving spending, and checking balances.

## Features

- **Standard ERC20 Functions**: 
  - `transfer`
  - `approve`
  - `transferFrom`
  - `balanceOf`
  - `allowance`
  
- **Minting Functionality**: Ability to mint new tokens.

## Prerequisites

- [Node.js](https://nodejs.org/) (for running local development tools, if needed)
- [MetaMask](https://metamask.io/) (for interacting with the Ethereum network)
- [Remix IDE](https://remix.ethereum.org/) (for developing and deploying smart contracts)

## Deployment

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/MyERC20Token.git
   cd MyERC20Token# MyERC20Token

2. **Open Remix IDE**:
   Go to Remix IDE.
   
3. **Upload Contract**:
   Upload the contract file (MyToken.sol) to Remix.

4. **Compile the Contract**:
   Use the Solidity compiler in Remix to compile the contract.

5. **Deploy the Contract**:
   Select the Sepolia network in MetaMask.
   Deploy the contract using Remix.

**Contract Address**
The contract is deployed on the Sepolia test network. You can view it on Etherscan:
https://sepolia.etherscan.io/tx/0x97bffcda4668d5561c57b316c0d7d31d12ce8ed32af4b62c8bb4d2297e730e27


**Usage**
Once deployed, you can interact with the token using the following functions:

- Transfer Tokens: Send tokens to another address.
- Approve Spending: Allow another address to spend tokens on your behalf.
- Transfer From: Transfer tokens from one address to another.
- Check Balance: View the balance of a given address.
- Check Allowance: Check how much a spender is allowed to spend.

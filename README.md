# Token Contract 

This is a simple Ethereum smart contract written in Solidity that implements a basic ERC20 token with additional functionality. The contract allows for minting, burning, and transferring tokens.

## Features

- **Minting Tokens**: The contract owner (deployer) can mint new tokens and assign them to specific addresses.
- **Burning Tokens**: Any token holder can burn (destroy) their tokens, reducing the total token supply.
- **Transferring Tokens**: Token holders can transfer their tokens to other addresses.

## Setup

1. **Deploying the Contract**: 
   - Deploy the contract onto the Ethereum blockchain. The constructor will automatically mint an initial supply of 5000 tokens to the deployer's address.

2. **Minting Tokens**:
   - As the contract owner, you can mint additional tokens and assign them to specific addresses using the `mintTokens` function.

3. **Burning Tokens**:
   - Any token holder can burn their tokens using the `burnTokens` function. This reduces the total token supply.

4. **Transferring Tokens**:
   - Token holders can transfer their tokens to other addresses using the `transferTokens` function.

## Events

- `TokensMinted`: Triggered when tokens are minted and assigned to an address.
- `TokensBurned`: Triggered when tokens are burned (destroyed) by a token holder.
- `TokensTransferred`: Triggered when tokens are transferred from one address to another.

## Usage

1. Deploy the contract onto the Ethereum blockchain.
2. Use the provided functions to mint, burn, and transfer tokens as needed.
3. Monitor events emitted by the contract for activity and updates.

## contact 

kumarljchethan@gmail.com

# myToken

## Overview

CustomToken is an ERC20 token created as part of a project to learn and implement token minting, transferring, and burning functionalities using Solidity and Hardhat.

## Features

- **Minting**: Only the contract owner can mint new tokens.
- **Transferring**: Any user can transfer tokens to another address.
- **Burning**: Any user can burn their own tokens.

## Interacting with the Contract

### Mint Tokens
Only the contract owner can mint tokens.
##
    function mintTokens(address to, uint amount) external onlyOwner


## Transfer Tokens
Any user can transfer tokens.
##
    function transferTo(address to, uint amount) external


## Burn Tokens
Any user can burn their own tokens.
##
    function burnTokens(uint amount) external

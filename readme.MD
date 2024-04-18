# ERC-20 Token Contract

Welcome to the Ethereum blockchain! This Solidity code provides a basic framework for an ERC-20 token, a standardized interface for fungible tokens on the Ethereum network. This contract is an excellent starting point for creating and managing your own digital assets.

## Overview

This ERC-20 token, named **MyToken** (symbol: MYT), is designed with flexibility in mind, featuring:
- **Name**: MyToken
- **Symbol**: MYT
- **Decimals**: 18
- **Total Supply**: Determined at the time of contract deployment.

## Contract Details

### Functions

- **Constructor**:
  - Initializes the token with the specified name, symbol, decimals, and initial supply.
  
- **Minting Function**:
  - Allows the contract owner to mint new tokens to a specified address.

- **Transfer Function**:
  - Enables the direct transfer of tokens from the sender to a recipient address.

- **Approval Function**:
  - Allows a token holder to authorize another address to spend tokens on their behalf.

- **Transfer From Function**:
  - Enables an approved spender to transfer tokens between addresses.

### Owner Management

- The contract specifies an owner, using the `onlyOwner` modifier to restrict access to certain functions.

## Getting Started

To utilize this contract:
- Deploy it to the Ethereum blockchain using suitable development tools like Truffle or Hardhat.
- Interact with the contract functionalities through Ethereum-compatible wallets or decentralized applications (DApps).

## Usage

- **Mint tokens**: Utilize the mint function to create new tokens.
- **Transfer tokens**: Use the transfer function to move tokens between addresses.
- **Authorize expenditures**: Approve others to manage tokens on your behalf with the approve function.
- **Spend approved tokens**: Execute transfers from one address to another using the transferFrom function.

## Security Considerations

- Secure the owner address properly; it should remain confidential.
- Conduct thorough testing and code reviews to ensure security and functionality before deploying on the Ethereum mainnet.

## License
This code is made available under the MIT License. Refer to the SPDX-License-Identifier header in the source code for more details.
## Contact 
Rahul lunthi :rahullunthi99@gmail.com

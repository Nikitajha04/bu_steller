# Stellar-Token
It's token build on stellar blockchain using Soroban SDK

# Soroban Token Contract

This repository contains the implementation of the Soroban Token contract, which is built on the Soroban blockchain platform.

## Overview

The Soroban Token contract provides a basic implementation of a fungible token on the Soroban blockchain. It includes functionalities such as minting, burning, transferring tokens between addresses, approving spending allowances, and querying token metadata.

## Features

- **Minting:** Allows the creation of new tokens and distribution to specified addresses.
- **Burning:** Enables token holders to permanently remove tokens from circulation.
- **Transferring:** Facilitates the transfer of tokens between addresses on the Soroban blockchain.
- **Allowances:** Allows token holders to approve other addresses to spend tokens on their behalf within certain limits.
- **Token Metadata:** Stores metadata such as token name, symbol, and decimals for easy identification and integration.

## Implementation Details

The contract is implemented in Rust using the Soroban SDK and Soroban Token SDK. It follows the Soroban contract design patterns and utilizes storage types for data management.

## Getting Started

To deploy and interact with the Soroban Token contract, you'll need:
- Access to a Soroban blockchain network
- Rust development environment set up with Soroban SDK
- Knowledge of Soroban contract development and deployment process

## Usage

1. **Initialization:** Deploy the contract and initialize it with the desired token parameters (name, symbol, decimal, admin address).
2. **Minting:** Mint new tokens by calling the `mint` function with the desired recipient address and token amount.
3. **Transferring:** Transfer tokens between addresses using the `transfer` or `transfer_from` functions.
4. **Allowances:** Approve spending allowances for other addresses using the `approve` function.
5. **Burning:** Burn tokens to reduce the token supply using the `burn` or `burn_from` functions.

## Testing

Unit tests are provided for certain functionalities of the contract to ensure correct behavior and functionality.

## Contributing

Contributions to the Soroban Token contract are welcome. Feel free to submit pull requests, report issues, or suggest improvements.

## License

This project is licensed under the [MIT License](LICENSE).



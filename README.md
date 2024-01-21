# ERC20 Token and Vault 

## Overview
This repository contains Ethereum smart contracts implementing an ERC20 token (`ERC20.sol`) and a simple vault (`Vault.sol`). The ERC20 token is named "Shashank SR" with the symbol "SSR," and the vault allows users to deposit and withdraw funds in exchange for shares.

## ERC20 Token (`ERC20.sol`)

### Functions
- **`transfer`**: Transfers tokens from the sender's account to the specified recipient.
- **`approve`**: Approves the spender to spend a certain amount of tokens on behalf of the owner.
- **`transferFrom`**: Transfers tokens from one address to another, with approval.
- **`mint`**: Mints new tokens and assigns them to the caller's account.
- **`burn`**: Burns a specified amount of tokens from the caller's account.

### Events
- **`Transfer`**: Emitted when tokens are transferred from one address to another.
- **`Approval`**: Emitted when an approval for token spending is granted.

## Vault (`Vault.sol`)

### Functions
- **`deposit`**: Allows users to deposit ERC20 tokens into the vault, minting shares in proportion to their deposit.
- **`withdraw`**: Allows users to withdraw ERC20 tokens from the vault, burning shares in proportion to the withdrawn amount.

### Variables
- **`token`**: The ERC20 token contract address associated with the vault.
- **`totalSupply`**: Total supply of shares in the vault.
- **`balanceOf`**: Mapping of user addresses to their respective share balances.

## Author

Shashank SR

shashanksr762@gmail.com

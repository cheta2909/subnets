## ERC20 Token and Vault Contract

This repository comprises two Solidity smart contracts: ERC20 and Vault, tailored for streamlined token management on the Ethereum blockchain.

### ERC20 Contract

The ERC20 contract embodies a standard implementation of the ERC20 token interface. It incorporates the following functionalities:

- **Total Supply**: Maintains a record of the total token supply.
- **Balances**: Maps addresses to their respective token balances.
- **Allowances**: Establishes a mapping between owner addresses and spender addresses along with the permitted token amounts.
- **Name, Symbol, and Decimals**: Provides metadata pertaining to the token.
- **Transfer**: Empowers users to transfer tokens to other addresses.
- **Approve**: Authorizes owners to grant spenders the ability to transfer tokens on their behalf.
- **TransferFrom**: Facilitates approved spenders to transfer tokens from the owner's address to another address.
- **Mint**: Enables the generation of new tokens.
- **Burn**: Facilitates the elimination of tokens.

### Vault Contract

The Vault contract furnishes a secure mechanism for managing ERC20 tokens. Key functionalities encompass:

- **Deposit**: Permits users to deposit tokens into the vault, receiving shares commensurate with their contribution.
- **Withdraw**: Allows users to withdraw tokens from the vault by relinquishing shares equivalent to the desired amount.

### Usage Guidelines

1. Deploy the ERC20 contract on the Ethereum blockchain.
2. Deploy the Vault contract, specifying the ERC20 token address during instantiation.
3. Engage with the contracts using Ethereum addresses to effectively administer tokens, deposit, and withdraw funds securely.

## Author

Chiranjeevi 

Email: cheta2909@gmail.com

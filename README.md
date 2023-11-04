# MyTokens Solidity Smart Contract

This Solidity smart contract, named "MyTokens," is a basic example of a token management contract. It allows for minting (creating) and burning (destroying) tokens associated with the token owner's Ethereum addresses.

## Smart Contract Details

- `_token_nm`: The name of the token is "Yogeshwar"

- `_token_abbr`: The abbreviation for the token is "Singh"

- `_tot_supply`: The total supply of tokens is tracked using this variable, initially set to 0.

### Token Balances

- `balance`: A mapping from Ethereum addresses to their respective token balances.

### Minting and Burning

- `mint(address Addr, uint Value)`: Use this function to mint (create) new tokens and assign them to a specific address. The total supply and the recipient's balance will be updated accordingly.

- `burn(address Addr, uint Value)`: Burn (destroy) a specific amount of tokens from a given address. The total supply and the address's balance will be adjusted accordingly.

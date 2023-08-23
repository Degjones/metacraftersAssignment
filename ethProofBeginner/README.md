# degjonesCryptoCoin 

This repository contains a simple Solidity smart contract for degjonesCryptoCoin, a basic cryptocurrency token. The contract implements functionalities for minting and burning tokens.

## Requirements

1. Public variables to store token details (Token Name, Token Abbreviation, Total Supply).
2. A mapping of addresses to balances.
3. A mint function to increase the total supply and the balance of a specified address.
4. A burn function to decrease the total supply and the balance of a specified address, with appropriate balance checks.

## Contract Details

- Token Name: degjonesCryptoCoin
- Token Abbreviation: DJCC

## Usage

1. Clone the repository: git clone https://github.com/Degjones/metacraftersAssignment/new/main/ethProofBeginner

2. Open the contract file `degjonesCryptoCoin.sol` in a Solidity development environment (e.g., Remix, VSCode with Solidity extension).

3. Deploy the contract to an Ethereum network (Ropsten, Rinkeby, etc.) using your preferred development tool.

4. Interact with the contract using the provided functions:
   - `mint(address _address, uint _value)`: Mint new tokens for the specified address.
   - `burn(address _address, uint _value)`: Burn tokens from the specified address.

## AUTHORS

degjones   

## License

This project is licensed under the MIT License.

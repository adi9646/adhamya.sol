# ETH BEG FINALPROJECT

# Description

This project is a Ethereum baesd smart contract coded in soldity for a any Token of your choice (In this case we have taken "Tron"TRX) . It includes basic functionalities for minting and burning tokens, allowing the total supply and individual balances to be managed.

# Requirements

## Public Variables:

tokenname: Stores the name of the token.

tokenabbrev: Stores the abbreviation of the token.

totalsupply: Stores the total supply of the token.

## Mappings:

balances: Maps addresses to their corresponding token balances.

## Functions:
mint(address _address, uint _value): Increases the total supply and the balance of the specified address by the given value.

burn(address _address, uint _value): Decreases the total supply and the balance of the specified address by the given value, ensuring the address has enough tokens to burn.

# Getting Started

## Installing

Clone the repository from Github or just copy and paste the code in any online compiler

Open Remix online editor (https://remix.ethereum.org/)

Copy and paste the code from the file to the online editor(remix) or any compiler of your choice.

Executing program (Remix editor)

Copy and Paste the program

Click solidity compiler in the left side panel and compile the program

Click Deploy & run transactions in the left side panel and Deploy the program

Use the provided functions to mint or burn tokens.

// To mint tokens

mintFunc(address addr, uint supplyValue)

// To burn tokens

burnFunc(address addr, uint supplyValue)

check Total Supply after minting or burning the tokens

# Help

For any issues, you can refer to the Remix documentation or common Ethereum development resources.


# Authors

Adhamya sanotch

[@22BCS15122] (adhi9646@gmail.com)


# License

This project is licensed under the MIT License - see the LICENSE.md file for details


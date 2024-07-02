# ETH BEG FINAL PROJECT

# Description

This project is a Ethereum baesd smart contract coded in soldity for a any Token of your choice (In this case we have taken "adi") . It includes basic functionalities for minting and burning tokens, allowing the total supply and individual balances to be managed.

# Requirements

## Public Variables:

1. tokenname: Stores the name of the token.

2. tokenabbrev: Stores the abbreviation of the token.

3. totalsupply: Stores the total supply of the token.

## Mappings:

balances: Maps addresses to their corresponding token balances.

## Functions:
1. mint(address _address, uint _value): Increases the total supply and the balance of the specified address by the given value.

2. burn(address _address, uint _value): Decreases the total supply and the balance of the specified address by the given value, ensuring the address has enough tokens to burn.

# Getting Started

## Installing

1. Clone the repository from Github or just copy and paste the code in any online compiler

2. Open Remix online editor (https://remix.ethereum.org/)

3. Copy and paste the code from the file to the online editor(remix) or any compiler of your choice.

4. Executing program (Remix editor)

5. Copy and Paste the program

6. Click solidity compiler in the left side panel and compile the program

7. Click Deploy & run transactions in the left side panel and Deploy the program

8. Use the provided functions to mint or burn tokens.

// To mint tokens

9. mintFunc(address addr, uint supplyValue)

// To burn tokens

10. burnFunc(address addr, uint supplyValue)

11. check Total Supply after minting or burning the tokens

# Help

For any issues, you can refer to the Remix documentation or common Ethereum development resources.


# Authors

Adhamya sanotch

[@22BCS15122] (adhi9646@gmail.com)


# License

This project is licensed under the MIT License - see the LICENSE.md file for details


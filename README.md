In the 2nd assessment of Meta Crafter we have to create a token. This repository contains a Solidity smart contract that defines a basic token named "Nobita". 
Below, you'll find details about the contract, including its features, instructions, and usage. Features: Token Details:Publicly accessible variables that 
store the token's name, abbreviation, and total supply. Balances Mapping: A mapping that keeps track of each address's token balance.
Mint Function: Increases the total supply and the balance of a specified address. Burn Function: Decreases the total supply and the balance
of a specified address, with a check to ensure sufficient balance.The contract is implemented in Solidity and includes the following key components: Public Variables
tokenName: The name of the token ("Nobita"). tokenAbbrv: The abbreviation of the token ("Nobi"). totalSupply: The total supply of tokens in existence.
Balances Mapping balances: A mapping from addresses to their respective token balances.
Mint Function The mint function increases the total supply and the balance of a specified address.
Burn Function The burn function decreases the total supply and the balance of a specified address, ensuring the balance is sufficient before performing the operation.

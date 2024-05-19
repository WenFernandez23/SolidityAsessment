Overview 

Contract Details
Prerequisites
Solidity version: 0.8.18
License: MIT

Variables
tokenName: A string representing the name of the token. In this case, it's "WEN".
tokenAbbrv: A string representing the abbreviation or symbol of the token. In this case, it's "NEW".
totalSupply: An unsigned integer representing the total supply of the tokens in existence.
balances: A mapping that stores the balance of tokens for each address.

Public Functions
mint
function mint(address _address, uint _value) public

This function allows new tokens to be created and assigned to a specified address. The total supply of the token is increased by the specified value, and the balance of the specified address is updated.

Parameters:
_address: The address to which the new tokens will be assigned.
_value: The number of tokens to be minted.

burn
function burn(address _address, uint _value) public

This function allows tokens to be destroyed from a specified address. The total supply of the token is decreased by the specified value, and the balance of the specified address is updated, provided the address has enough tokens to burn.

Parameters:
_address: The address from which the tokens will be burned.
_value: The number of tokens to be burned.

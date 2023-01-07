# Ether Vault to Transfer Etherium

This is a vault Smart contract that remembers the balance of each address that deposits ETH to it and lets them withdraw it when they want to. 

## Overview


### Usage

**deposit**\
The deposit () function lets an account send ETH when calling the function. It saves the amount sent by the sender in a mapping called balances. 

**withdraw**\
The withdraw() function checks the amount against the address of the caller in the balances mapping, sends an equivalent amount of ETH from the contract to the caller, and then updates the balance of the caller to zero.

## License

This Contract is released under the [MIT License](LICENSE) and thanks to [OpenZeppelin](https://openzeppelin.com).


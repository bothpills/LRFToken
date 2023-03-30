# LRFToken

This is a smart contract for the LRF Token implemented in Solidity. The contract implements the ERC20 token standard with the following functionalities:

GETTERS:
totalSupply(): Returns the total supply of LRF Tokens.
balanceOf(address account): Returns the balance of LRF Tokens held by a specific account.
allowance(address owner, address spender): Returns the amount of LRF Tokens that the owner has approved for the spender.

FUNCTIONS:
transfer(address recipient, uint256 amount): Transfers a specified amount of LRF Tokens from the sender's account to the recipient's account.
approve(address spender, uint256 amount): Approves the spender to spend a specified amount of LRF Tokens from the sender's account.
transferFrom(address sender, address recipient, uint256 amount): Transfers a specified amount of LRF Tokens from the sender's account to the recipient's account on behalf of the owner.

EVENTS:
Transfer(address indexed from, address indexed to, uint256 value): Emitted when LRF Tokens are transferred from one account to another.
Approval(address indexed owner, address indexed spender, uint256 value): Emitted when the owner approves the spender to spend a specified amount of LRF Tokens.
The contract deploys with an initial total supply of 10 ether and sets the balance of the deployer to the total supply. The symbol of the token is "LRF" and the number of decimal places is 18.

The MyToken contract is a custom token implementation on the Ethereum blockchain. It adheres to certain requirements and utilizes Solidity for the creation, minting, and burning of a token named "ALPHA" with the abbreviation "ALP". This contract allows for managing the total supply of tokens and tracking individual balances through public variables and mappings.

**Token Details -**

- Token Name: ALPHA<br/>
- Token Abbreviation: ALP<br/>
- Total Supply: Initially set to 0 (modifiable through minting and burning functions)

**Balance Mapping -**

- Monitors and maintains the balance of each address.

**Mint Function -**

- Parameters: Address and value<br/>
- Functionality:<br/>
1. Increases the total supply of tokens.<br/>
2. Adds tokens to the balance of the specified address.

**Burn Function -**

- Parameters: Address and value<br/>
- Functionality:<br/>
1. Decreases the total supply of tokens.<br/>
2. Removes tokens from the balance of the specified address.<br/>
3. Ensures the specified address has a sufficient balance before burning tokens.

**Video Tutorial -**

For more details on how to deploy and interact with this contract, refer to the accompanying documentation and video tutorial:


https://www.loom.com/share/c2cd9b3e5c364dfea568cf21ec3560a4?sid=cdf40eeb-f512-4dfb-8905-6e780956e60a 

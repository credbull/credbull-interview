# Credbull Coding Exercise

## Objective 
- **Think** about a problem and **show** how you go about solving it.  
- Have a **dialogue** with one of the Credbull Engineers about your solution, thought processes, roadbumps, etc.
- Time-box this to a few hours only.  We respect your free time, and don't want this to be overly burdensome.  

## Coding Exercise
- [ ] Create a Solidity contract that accepts and tracks deposits and allows the depositor to withdraw their deposited amount.  
- [ ] Create an App in Typescript and ether.js (or similar) that can interact with your contract.
- [ ] Add business logic to your contract.  Choose 1-2 from below, or come up with your own! 
    - Min transfer amount - only accept deposits above a certain minimum amount
    - Max total amount - only accept transfers into a contract when the total contract value is below the maximum
    - Yield - on withdrawal, depositors receive their deposit plus a proportional amount of any "excess" balance in the contract  
    - Whitelist - only allow transfers from whitelisted addresses
    - Fees - keep 1% of deposits as fees.


## Implementation Ideas
Feel free to develop the solution however you like.  Credbull used the following, they may also help you!
* Credbull uses [OpenZepplein's ERC4626](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/extensions/ERC4626.sol) implementation of the [erc-4626 Vault Standard](https://ethereum.org/en/developers/docs/standards/tokens/erc-4626/) as the basis for our contracts.  
* [scaffold-eth-2](https://github.com/scaffold-eth/scaffold-eth-2) is great for rapid prototyping.  This is a fork of the foundry version, but you can fork the hardhat version as well.


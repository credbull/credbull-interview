# Credbull Coding Exercise

## Objective 
- **Demonstrate** your problem solving and developer skills.     
- Have a **conversation** with one of the Credbull Engineers about your solution, thought processes, roadbumps, etc.
- Time-box the exercise to 2-3 hours.  We respect your free time, so don't want this to be overly burdensome.  

## Coding Exercise
- [ ] Create a Solidity contract that accepts and tracks deposits and allows the depositor to withdraw their deposited amount.  
- [ ] Create an App in Typescript and ether.js (or similar) that can interact with your contract.
- [ ] Implement **only 1-2 features** from below.  Or come up with your own! 
    - Min transfer amount - only accept deposits above a certain minimum amount
    - Max total amount - only accept transfers into a contract when the total contract value is below the maximum
    - Yield - on withdrawal, depositors receive their deposit plus a proportional amount of any "excess" balance in the contract  
    - Whitelist - only allow transfers from whitelisted addresses
    - Fees - keep 1% of deposits as fees.


## Implementation Ideas
Develop the solution however you like.  Credbull have used the following, they may also help you!
* Credbull uses [OpenZepplein's ERC4626](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/extensions/ERC4626.sol) implementation of the [erc-4626 Vault Standard](https://ethereum.org/en/developers/docs/standards/tokens/erc-4626/) as the basis for our contracts.  
* [scaffold-eth-2](https://github.com/scaffold-eth/scaffold-eth-2) is great for rapid prototyping.  This repo is based on the foundry, but there's a hardhat version as well.


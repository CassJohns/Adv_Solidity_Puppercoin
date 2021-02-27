# Adv_Solidity_Puppercoin

## Smart Contracts 

Using Remix, I created ERC20 coin called "PupperCoin." using the ERC20Mintable and ERC20Detailed contracts to create the ERC20 Puppercoin.

After creating the ERC20 coin, I launched a hypothetical crowdsale of the PupperCoin token to fund the network development. For this contract, I imported the Puppercoin contract, and inhereted the  Crowdsale, CappedCrowdsale, TimedCrowdsale, RefundableCrowdsale, and MintedCrowdsale from OpenZeppelin.  This required setting up variables for the token, rate (set to 1), symbol, goal to be raised from the crowdsale, and open and close times. The contract mints the tokens automatically and distributes them to buyers, allowing users to to send ETH and get PupperCoin back.

## Deployment 

First I deployed the PupperSaleDeployer contact, inputting the token name, symbol and wallet address from above.  Once this contract was deployed I took the pupper sale address, copied it, and input it into the Alt Address.  Then I copied the token address and input it into the Alt address for the  PupperSale contract. 

I added the PupperCoin as a custom token to my Metamax and Mycrypto accounts, and then sent ether to the contract, making sure I hit my goal of 10 Ether by leveraging my prefunded accounts from Ganache.  I deployed the crowdsale to the Ropsten testnet when deploying my contracts. 


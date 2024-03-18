# Project Template 
- 10000 supply
- limit to 1 mint per wallet 
- price is 0.1 sol 

# Deployment Plan
set wallet address in config.json

wallet.json

place assets in assets folder, `assets/`

solana config set --url <YOUR_QUICKNODE_URL>

make sure wallet is funded enough

`sugar validate`

`sugar upload` 

`sugar deploy`

`sugar verify`

`sugar guard add`

change env variables in the minting website 

## Test Plan on devnet

### Test case: can't mint two NFTs, can't mint twice 
Wallets that can mint, can only mint one. 

Minting two or again fails.

### Test case: max supply reached, no more can get minted

Change supply to a smaller number and see if can't mint greater than the supply 

### Test case: only wallets holding the required NFT can mint 


# config.json 
Mint Limit: Specifies a limit on the number of mints per wallet.

https://docs.metaplex.com/programs/candy-machine/available-guards/mint-limit

Sol Payment: Set the price of the mint in SOL.

https://docs.metaplex.com/programs/candy-machine/available-guards/sol-payment

Nft Gate: 



## folder `assets/`

example files:

0.png

0.json

1.png

1.json

2.png

2.json


## Links 

Solana Devnet Faucet [https://faucet.solana.com/](https://faucet.solana.com/)

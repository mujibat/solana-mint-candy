# Metaplex Candy Machine Reference UI

# Project Title

This is the UI of the Candy Machine Minting Setup

## Description

For users to mint nfts.

## Getting Started

```
yarn install
yarn start
```


### Executing program
- Create a .env file with these:
```
REACT_APP_CANDY_MACHINE_ID=<YOUR_CANDY_MACHINE_PUBKEY>
REACT_APP_SOLANA_NETWORK=devnet
REACT_APP_SOLANA_RPC_HOST=<YOUR_QUICKNODE_DEVNET_ENDPOINT>
```
If you don't remember your Candy Machine ID, you should be able to find it in cache.json in the program.candyMachine field. 

- You'll need devnet SOL in your Phantom wallet to mint an NFT. You can use Solana CLI to airdrop to your Phantom wallet by entering this command in your terminal: 
```
solana airdrop 1 YOUR_PHANTOM_WALLET_ADDRESS
```


## License

This project is licensed under the MIT License - see the LICENSE.md file for details

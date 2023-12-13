# Solana-Bootcamp-Final-Project
Above is a NFT project for cryptographic puzzle . Intially we have a puzzle, and we will get an image once we have solved the puzzle and its description too . One can also request for hints if they dont get an idea!!!!
# Solana NFT Project

## Connect to Devnet

To connect to the Solana Devnet, use the following command:

 ```bash
 solana config set --url devnet
 ```
Deploying a contract will require some tokens. Obtain Devnet tokens using the command:
```bash
solana airdrop 1
```
## Deploy the Contract
After obtaining Devnet tokens, deploy the contract with the following command:
```bash
solana program deploy target/deploy/nft.so
```
now save the `YOUR_PROGRAM_ID`
## Install Node Modules
Install the required node_modules dependencies by running:
```bash
yarn install
```
Additionally, install the @solana/spl-token package manually using:
```
yarn add @solana/spl-token
```
## Test the NFT Contract
With the contract and frontend set up, test the NFT contract by executing the client:

```bash
npx ts-node app.ts <YOUR_PROGRAM_ID>
```





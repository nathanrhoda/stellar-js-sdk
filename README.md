# Stellar Lumens JavaScript SDK
Playing with Stellar JavaScript SDK - Stellar Lumens: ES7 async/await example.
This example creates two accounts on the testnet and let's the friendbot give them testnet tokens.
Next, we transfer a small amount from one account to another.

## Installation
Execute in terminal inside the root of the project:
`npm install`

## Start & Usage
Again in terminal at root:
`npm start`

## Postman collections included for easy execution of endpoints
1. CreateKey : Create public and private key for wallet this is done seperately so you can store private public key so you can store private key

2. Create Account & Deposit funds : Creates the account in stellar testnet and loads it with 10000 XLM

3. Transactions: Requires you to enter sr and des public keys as well as amount. Please not that because you have to sign transactions you will need to have a private key on hand to sign it. So to get this working end to end you will need to add your wallet details in the wallets directory and reference it from the makepayment method on app.js line 66

4. History: Gives you a summary of all transactions that has happened on the account with public key that you pass in



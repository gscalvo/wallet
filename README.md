# Multi-Blockchain Wallet in Python

## Background

We will be building a muti-coin wallet for multiple addresses in Python using hd-derive-wallet

## Required Libraries

* Web3
* Bit

## Process 

* Clone hd-derive-wallet
* Download starter code
* Write a function to convert privkey to objects web3 and bit can use
* Write three functions
    * First function, derive_wallets, derives wallets from the network
    * Second function, create_txt, creates a message for a transaction
    * Last function, send_txt, signs the transaction and sends it

## Test Messages

### Bitcoin Test Net

![bitcoin_transaction](/btc_testnet_transaction_proof.PNG)

### Ethereum Test Net

![eth_transaction](/eth_transaction_proof.PNG)

### Local PoA Ethereum Transaction

![mycrypto_transaction](/mycrypto_transaction_proof.PNG)
# CSE-598-LedgerLegends

## Fake Product Identification using Blockchain

## Requirements
1. Truffle
2. Solidity
3. Ganache
4. Node
5. npm
5. Web3.js
6. Metamask browser extension

## Setup

1. Clone the repo
```
https://github.com/Shashank-HK/CSE-598-LedgerLegends.git`
```


2. Go into the folder and install node modules
```
npm install
```

3. Setup local blockchain using Ganache
    - Create new workspace
    - In Truffle Projects, click on Add Project and choose `truffle-config.js` file from our repo
    - Click on Start

4. Compile and deploy smart contract

```
truffle compile
truffle migrate
```

5. Start the web server
```
npm run dev
```

6. In browser, open Metamask
    - Add new test network manually
        
        -  Network name - Same as the one in Ganache
        - RPC Url - Same as the one in Ganache (default HTTP://127.0.0.1:7545)
        - Chain ID - 1337
        - Currency Symbol - ETH
    
    - After adding network, switch to that network
    - Click on Accounts -> Add an account -> Import account
    - Add private key of any account shown in Ganache 
7. Make sure you are on our website (localhost:3000). In Metamask extension, click on Connected Sites -> Manually connect to current site

8. Setup done. Explore the website and its functionalities
# TOKEN DE IDENTIDAD DIGITAL NO FUNGIBLE PARA PERSONA FÍSICA O PERSONA MORAL. (iNFT)

**Index**   
1. [Introduction](#introduction)
2. [Keywords](#keywords)
3. [Tools](#tools)
4. [Acknowledgements & Contributions](#acknowledgements)
5. [References](#references)
6. [Technical Stuff](#technical)

## Introduction<a name="introduction"></a>

This is an official Ethereum Non-Fungible Token for Digital Identity Verification of physical and moral persons through the global internet network, based on [ERC-721 Non-Fungible Token Standard](https://eips.ethereum.org/EIPS/eip-721).

This repository contains the necessary code to create this kind of tokens.

## Keywords<a name="keywords"></a>

- NFT
	- "It is a unit of data on a digital ledger called a blockchain, where each NFT can represent a unique digital item, and thus they are not interchangeable." by Wikipedia.

- Blockchain
	- "It is a growing list of records, called blocks, that are linked using cryptography." by Wikipedia.

- CryptoIdentity
	- "Online human identification on the blockchain." by Diana Elena Pinto Apolinar.

## Tools<a name="tools"></a>

[NPM](https://nodejs.org)

[Ganache](https://www.trufflesuite.com/docs/ganache/quickstart)

[Truffle Suite](https://www.trufflesuite.com)

[Metamask](https://metamask.io)

[ERC721](http://erc721.org)

[OpenZeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts)

## Acknowledgements & Contributions<a name="acknowledgements"></a>

The information in this document is patented and an effort from [Diana Elena Pinto Apolinar](https://www.apokochito.dev), I welcome contributions, revisions, and feedback.

Please submit a pull-request or issue if you would like to make any changes or have any comments (please don’t send pull-requests which change whitespace or line-endings etc).

## References<a name="references"></a>

1. Proposals, E. (2021). EIP-721: ERC-721 Non-Fungible Token Standard. Retrieved 19 March 2021, from https://eips.ethereum.org/EIPS/eip-721

## Technical Stuff<a name="technical"></a>

### Step 1. Clone the project
```bash
HTTPS - https://github.com/apokochito/nftIdentity.git
SSH - git@github.com:apokochito/nftIdentity.git
```

### Step 2. Install dependencies
```bash
cd nftIdentity
npm install
```

### Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.

### Step 4. Compile & Deploy Election Smart Contract
```truffle migrate --reset``` You need to migrate contract in order to deploy in your local system

### Step 5. Configure Metamask
- Unlock Metamask <br/>
- Connect metamask to your local Etherum blockchain provided by Ganache.<br/>
- Import an account provided by ganache.<br/>

### Step 6. Run the Front End Application
```
cd src
npm start
```

### Watch it on your browser
Now you Blockchain web-app is serverd on http://localhost:8000

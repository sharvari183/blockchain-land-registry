# Blockchain Land Registry

A decentralized land registry application designed to provide secure, transparent, and tamper-resistant land ownership records using blockchain technology.

## Project Overview

The Blockchain Land Registry allows users to register and verify land ownership records through a web-based application.

Instead of relying only on a traditional centralized database, the project uses a Solidity smart contract to store land registration data on an Ethereum-compatible blockchain network.

## Features

- Register land ownership records
- Store owner name, location, and land area
- Generate unique land record IDs
- Record the wallet address that registers the land
- Store registration timestamps
- View registered land records
- MetaMask wallet integration
- Smart contract-based data storage
- Transparent blockchain transactions

## Technology Stack

### Frontend
- React.js
- Vite
- JavaScript
- CSS

### Blockchain
- Solidity
- Ethereum-compatible blockchain
- Hardhat
- Ethers.js
- MetaMask

### Development Tools
- Visual Studio Code
- Node.js
- npm
- Git
- GitHub

## Project Structure

```text
Blockchain-Land-Registry/
│
├── contracts/
│   └── LandRegistry.sol
│
├── scripts/
│   └── deploy.js
│
├── artifacts/
│   └── LandRegistry.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── App.css
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── compile.js
├── hardhat.config.js
├── package.json
└── README.md

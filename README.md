# Staking DApp

This project is a decentralized staking application (DApp) developed as part of my Web3 learning journey. The application allows users to connect their MetaMask wallet, stake ETH, view their staked balance, and withdraw their funds through a smart contract deployed on the blockchain.

The project demonstrates the integration of Solidity smart contracts with a React frontend using Ethers.js.

## Features

* Connect MetaMask Wallet
* Stake ETH into the smart contract
* View staked balance
* Withdraw staked ETH
* Real-time blockchain interaction
* User-friendly web interface

## Technologies Used

### Blockchain

* Solidity
* Remix IDE
* MetaMask

### Frontend

* React.js
* Vite
* Ethers.js

### Deployment

* GitHub
* Vercel

## Smart Contract

The smart contract maintains individual user balances and allows users to stake and withdraw ETH securely.

### Functions

* `stake()` – Stake ETH into the contract
* `withdraw(uint256 amount)` – Withdraw staked ETH
* `balances(address)` – View balance of a user
* `getBalance(address)` – Retrieve staked balance

## Project Structure

```text
Staking_Dapp/
│
├── contracts/
│   └── Staking.sol
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

## To Run the Project

### Clone Repository

```bash
git clone https://github.com/mummanavasanthi/Staking_Dapp.git
```

### Navigate to Frontend

```bash
cd frontend
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

## Workflow

1. Connect MetaMask Wallet
2. Enter ETH Amount
3. Stake ETH
4. Check Staked Balance
5. Withdraw ETH
6. Verify Updated Balance

## Output
<img width="514" height="321" alt="Screenshot 2026-06-04 113801" src="https://github.com/user-attachments/assets/16749055-2fc6-4fcc-86c9-3b104071e86d" />

This project helped to understand the fundamentals of decentralized applications and blockchain development. It demonstrates how smart contracts can be integrated with modern web technologies to build secure and interactive Web3 applications.

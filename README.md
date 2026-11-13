# 🍽️ TheRestaurant

A decentralized blockchain booking system for making and managing restaurant reservations on an Ethereum testnet.

---

## 📖 Overview

**TheRestaurant** leverages Ethereum smart contracts to provide a transparent, tamper-proof restaurant reservation experience. By recording bookings on-chain, the platform eliminates double-bookings, ensures verifiable reservation ownership through Web3 wallets, and removes reliance on centralized intermediaries.

---

## ✨ Features

* **Web3 Wallet Authentication:** Connect seamlessly using MetaMask or any Ethereum-compatible wallet.
* **On-Chain Reservations:** Create, view, and manage table bookings directly via smart contracts on an Ethereum testnet.
* **Transparent Availability:** Real-time, verifiable slot availability stored on the blockchain.
* **Testnet Ready:** Built and tested for safe deployment on Ethereum test networks (e.g., Sepolia) using test ETH.

---

## 🗂️ Project Structure

```text
TheRestaurant/
├── eth-restaurant/     # Smart contracts, deployment scripts, and blockchain configuration
├── my-project/         # Supporting application modules / backend services
├── therestaurant/      # Frontend Web3 user interface
└── README.md
```

---

## 🛠️ Tech Stack

* **Blockchain & Smart Contracts:** Solidity, Ethereum Testnet
* **Web3 Integration:** Ethers.js / Web3.js, MetaMask
* **Frontend:** JavaScript / React / HTML & CSS
* **Development Environment:** Node.js, Hardhat / Truffle

---

## 🚀 Getting Started

### Prerequisites

* [Node.js](https://nodejs.org) (v16+ recommended)
* [npm](https://npmjs.com) or [yarn](https://yarnpkg.com)
* [MetaMask](https://metamask.io) browser extension configured for an Ethereum testnet (e.g., Sepolia) with test ETH from a faucet.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd TheRestaurant
   ```

2. **Install dependencies for the smart contracts:**
   ```bash
   cd eth-restaurant
   npm install
   ```

3. **Install dependencies for the frontend:**
   ```bash
   cd ../therestaurant
   npm install
   ```

### Running Locally

1. **Compile and deploy the smart contracts** (from `eth-restaurant/`):
   ```bash
   npx hardhat compile
   npx hardhat run scripts/deploy.js --network sepolia
   ```
   *(Copy the deployed contract address and update your frontend configuration/ABI if needed).*

2. **Start the frontend application** (from `therestaurant/`):
   ```bash
   npm start
   ```

3. Open your browser, connect your MetaMask wallet on the matching testnet, and make a reservation!

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com) or submit a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

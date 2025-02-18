# 🏗️ StorageFactory Smart Contract

This project implements a **Storage Factory** smart contract in Solidity, allowing users to create and manage multiple instances of the `SimpleStorage` contract. The contract provides functions to store and retrieve values from dynamically created `SimpleStorage` instances.

## 📌 Features

✅ Deploys multiple `SimpleStorage` contracts dynamically.  
✅ Stores values in specific contract instances.  
✅ Retrieves stored values from specific contract instances.  
✅ Implements a **Factory Pattern** for efficient smart contract management.

---

## 📂 Project Structure

---

## 📝 Smart Contract Explanation

### 1️⃣ **StorageFactory.sol** (Main Contract)
The `StorageFactory` contract allows users to **deploy**, **store**, and **retrieve** data from multiple `SimpleStorage` contracts.

### 2️⃣ **SimpleStorage.sol** (Storage Contract)
Each instance of `SimpleStorage` stores a single `uint256` value and provides functions to update and retrieve it.

---

## ⚡ How It Works

### **1️⃣ Deploy the StorageFactory Contract**
Deploy `StorageFactory.sol` on a blockchain (e.g., Ethereum, Polygon, TON, etc.).

### **2️⃣ Create a SimpleStorage Contract**
Use the `createSimpleStorageContract()` function to deploy a new `SimpleStorage` contract.

solidity

storageFactory.createSimpleStorageContract();

## 🚀 Deployment & Testing
### 🛠️ Prerequisites
Solidity Compiler (solc)
Remix IDE or Hardhat
Ethereum Wallet (e.g., MetaMask, TON Wallet)
Test Network (Goerli, Sepolia, or TON Testnet)
## 📝 Steps to Deploy
Open Remix IDE or set up Hardhat.
Compile StorageFactory.sol.
Deploy it to a test network or local blockchain.
Interact with the contract using functions like createSimpleStorageContract(), sfStore(), and sfGet().
## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request. 🚀

## 📬 Contact
If you have any questions or suggestions, feel free to reach out! 😊
### 📧 Email: nifeesleman@ghmail.com
### 💬 Telegram: @nifeesleman





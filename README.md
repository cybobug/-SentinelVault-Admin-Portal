# 🛡️ SentinelVault Admin Portal

> A blockchain-integrated, self-defensive honeypot dashboard with real-time threat monitoring, decentralized backup management, and emergency wipe functionality.
---

## 🚀 Project Overview

**SentinelVault** is your fortress's control room — a cutting-edge admin portal designed to:

- 📊 Visualize threats in real-time  
- 🔐 Securely authenticate administrators  
- 💾 Manage backups across **IPFS**, **Arweave**, and local storage  
- ⛓️ Log and verify data on the **blockchain**  
- 🧨 Execute emergency wipe & backup procedures with one click  

---

## 🧩 Tech Stack

| Layer       | Tools/Tech                                             |
|-------------|--------------------------------------------------------|
| Frontend    | HTML, CSS (Bootstrap 5), Vanilla JS, Web3.js, MetaMask |
| Backend     | Node.js, Express, JWT, Bcrypt, CORS, Body-parser       |
| Blockchain  | MetaMask, Ethereum/Polygon, Smart Contract (logBackup) |
| Storage     | IPFS, Arweave, Local Encrypted                         |

---

## 🌟 Features

### 🔐 Admin Authentication
- Secure login with password hashing (bcrypt)
- JWT-based session handling

### 🛡️ Threat Monitoring
- Visual dashboard for threat logs
- IP banning on repeated or high-risk attempts
- Brute-force & injection detection (simulated)

### 💾 Backup Management
- Manual and scheduled backups
- Choose between IPFS, Arweave, or local storage
- Detailed backup history with size & status

### ⛓️ Blockchain Integration
- MetaMask wallet connect
- Log & verify backups on-chain
- Contract event listeners and real-time sync

### 🧨 Emergency Response
- Initiate backup + system wipe if breach detected
- Smart contract-based recovery logs

---

## ⚙️ Getting Started

### 📦 Prerequisites

- Node.js (v14+ recommended)
- MetaMask extension
- IPFS / Arweave setup (for full deployment)

### 🛠 Installation

```bash
git clone https://github.com/cybobug/SentinelVault-Admin-Portal
cd SentinelVault-Admin-Portal
npm install
```
### ▶️ Run the Project

```bash
npm run dev   # Development mode with nodemon
npm start     # Production server

Open index.html in your browser.
```

### 🔗 Blockchain Setup

- Replace the contractAddress placeholder in index.html
- Ensure contractABI matches your deployed smart contract
- Connect MetaMask to the correct network (Goerli, Polygon, etc.)

### 📄 License

This project is licensed under the MIT License.

### 👥 Author

Crafted with 💻 and 🧠 by Garvit Haswani
✨ Contributions and stars are welcome!

### ⚠️ Note

This project includes mock implementations for blockchain logging and IPFS backup. For production, integrate:

- Smart contracts using Solidity
- IPFS/Arweave SDKs or services like Infura/Web3.Storage
- Secure signing & real backup storage pipelines

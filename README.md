# 🐹 CavieChain  
### A Custom Cosmos-SDK Blockchain for Experimentation, Development & Innovation

CavieChain is a fully custom blockchain built with the Cosmos SDK and Ignite CLI.  
It uses a lightweight, modular architecture that makes it ideal for:

- Blockchain experimentation  
- Custom module development  
- Tokenomics research  
- Learning the Cosmos SDK  
- Prototyping IBC-ready application-specific chains  

CavieChain runs using a custom native token **`ucavie`**, supports full staking, governance, and bank modules, and is powered by CometBFT for consensus.

---

## 🚀 Features

- **Cosmos SDK v0.53** — the newest stable SDK
- **Custom native token:** `ucavie`
- **Proof-of-Stake (PoS)** with validator self-delegation
- **Full ABCI+ Application**
- **Custom module scaffolding** available under `x/cavie`
- **Key management** via Cosmos SDK keyring
- **Clean development environment** using Ignite CLI
- **Automatic Tendermint networking & block production**

---

## 📦 Requirements

- **Go 1.24+**
- **Ignite CLI**
- Linux or macOS environment (recommended)

---

## 🛠️ Build CavieChain

```bash
git clone https://github.com/tarunharit/cavie-chain
cd cavie-chain
ignite chain build


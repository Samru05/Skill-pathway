# 🔐 LangExchangeEscrow Smart Contract

## 📘 Description

The `LangExchangeEscrow` contract is a simple, trustless escrow system built on the Aptos blockchain. It is designed to facilitate secure peer-to-peer **language exchange agreements** between two users, where both parties deposit a fixed amount of tokens into escrow before beginning the exchange.

This contract ensures **mutual commitment** from both users by locking funds on-chain, promoting accountability in informal educational exchanges.

## 🎯 Vision

The vision behind this smart contract is to enable **trustless collaboration** in global language learning communities. By requiring both parties to commit tokens, it:
- Ensures seriousness and accountability from both sides.
- Eliminates the risk of one party ghosting or failing to deliver after the other has invested time.
- Sets the foundation for **decentralized, secure, and incentive-aligned language exchanges**.

## 🔮 Future Scope

This contract can be extended and improved with the following features:
- **Fund Release Mechanism**: Automatically or manually release funds upon session completion or mutual agreement.
- **Dispute Resolution**: Introduce a mediator or DAO-based voting mechanism to resolve conflicts.
- **Rating System**: Let users rate each other post-session, building reputation.
- **Session Scheduling and History Tracking**: Store timestamps, session counts, and history of interactions.
- **Dynamic Deposits**: Allow users to specify different deposit amounts or use other token types.

## 📍 Contract Address
0x3455d7c19380574c41400d323dca610910c4aa636dbb52dbe62765fffc2f27fd
> **Deployed Address:** `0x123`  
> *(Replace with actual address after deploying to Aptos Testnet or Mainnet)*

---

### 🔧 Compile Instructions

1. In your `Move.toml`, ensure the following:
   ```toml
   [addresses]
   MyModule = "0x123"

   ##screenshot
   <img width="1623" height="822" alt="image" src="https://github.com/user-attachments/assets/6e0cbfa4-8a7d-4535-87ab-f27b924802d1" />

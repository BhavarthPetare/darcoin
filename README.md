# Darcoin 💠
*A privacy-first cryptocurrency prototype for the modern web.*

Darcoin is a **stealthy rollup-style currency** designed to explore privacy in blockchain.  
Instead of exposing all transaction details like Bitcoin, Darcoin uses **Merkle commitments** and (eventually) **zk-SNARK proofs** to enable shielded transfers.

---

## 🚀 Features (Planned Roadmap)
- [x] **Smart contract** to store Merkle root + nullifiers
- [x] **Backend** API to build Merkle tree from transactions
- [x] **Frontend wallet** to create & send commitments
- [ ] Add zk-SNARK proof verification
- [ ] Batch transaction aggregator
- [ ] Rust/WASM Merkle tree for performance

---

## 📂 Project Structure
- **contracts/** → Solidity smart contracts (Hardhat)
- **backend/** → Node.js/Express API (Merkle logic, zk integration)
- **frontend/** → React + Tailwind wallet UI
- **docs/** → Diagrams + design notes
- **scripts/** → Deployment helpers

---

## 🛠 Tech Stack
- **Solidity** (Hardhat) – Smart contracts
- **TypeScript / Node.js** – Backend API
- **React + Tailwind** – Frontend wallet
- **snarkjs** – zk-SNARK library for proofs
- **Rust (optional)** – High-performance Merkle module (WASM)

---

## 📜 License
MIT – Free to use, fork, and improve.

---

## ✨ Vision
Darcoin is a student-built prototype exploring **private transactions on public blockchains**.  
It’s not meant for production use — just a demonstration of how **cryptography + blockchain** can merge to create next-gen money.

---

## 🔮 Roadmap
- Step 1: Repo + Skeleton ✅
- Step 2: Mocked pipeline (frontend → backend → contract)
- Step 3: zk Commitment proofs
- Step 4: Optimizations (batching, WASM modules)
- Step 5: Demo + Whitepaper-lite

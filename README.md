# Solana Development

This repository is entirely dedicated to **:contentReference[oaicite:0]{index=0} development**.

It is used for learning, experimenting, and understanding how Solana programs (smart contracts) are built, deployed, and interacted with using the official Solana ecosystem tools.

---

## Purpose

- Learn Solana’s programming model
- Write on-chain programs (smart contracts)
- Understand accounts, instructions, and transactions
- Interact with Solana programs from the client side
- Explore modern Solana tooling and workflows

This repository is for **educational and experimental use** only.

---

## Solana Development Stack

### Blockchain
**:contentReference[oaicite:1]{index=1}** is a high-performance Layer 1 blockchain focused on speed and low transaction costs.

- Account-based architecture
- High throughput and low latency
- Programs are stateless; data is stored in accounts

---

### Smart Contracts (Programs)
Solana smart contracts are called **programs** and are written in **:contentReference[oaicite:2]{index=2}**.

Rust is used to:
- Define program logic
- Validate instructions and accounts
- Update on-chain state

Programs compile to BPF bytecode and run inside the Solana runtime.

---

### Framework
**:contentReference[oaicite:3]{index=3}** is used to simplify Solana development.

Anchor provides:
- Reduced boilerplate in Rust
- Automatic account validation
- IDL generation
- Built-in testing tools

---

### Client Side
Client code is written in **JavaScript / TypeScript**.

It is used to:
- Send transactions
- Call program instructions
- Read blockchain data

Common libraries:
- `@solana/web3.js`
- Anchor client SDK

---

### Tooling

- **Solana CLI**
  - Wallet and keypair management
  - Program deployment
  - Network configuration

- **Anchor CLI**
  - Project initialization
  - Build and deploy programs
  - Run local tests

---

## Networks

This repository uses:
- Localnet
- Devnet

Mainnet is not used.

---

## License

MIT License

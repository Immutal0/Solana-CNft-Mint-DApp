# Solana CNFT Chat System

A messaging system built on Solana CNFT Mint using **Next.js**, **Tailwind CSS**, and **Solana/Web3**. This project utilizes the Solana blockchain and the **Metaplex SDK** to manage compressed non-fungible tokens (CNFTs), allowing users to upload metadata and create CNFTs.

## 📜 Description

This repository provides a baseline for a messenger system based on Solana CNFT Mint. It allows users to mint CNFTs on the Solana blockchain, manage metadata, and interact with the platform using Web3 technologies. 

---

## ⚙️ Setup

### 1. Set Up Environment Variables

To configure the application, you'll need to set the following environment variables:

- **`WALLET_PRIVATE`**: Administrator wallet private key for CNFT mint fee transactions.
- **`MAINNET_RPC`**: The Solana Mainnet RPC URL.
- **`PINATA_JWT`**: JSON Web Token for uploading content to Pinata (used for storing IPFS metadata).
- **`MERKLE_TREE_PUBKEY`**: Merkle Tree Public Key for your CNFT minting process.

### 2. Install Dependencies

Make sure you have the required dependencies installed. You can install them using either `yarn` or `npm`:

```bash
yarn install
# or
npm install
```

### 3. Run the Application

After installing dependencies and setting up the environment variables, you can run the application locally with:

```bash
yarn dev
# or
npm run dev
```

This will start the Next.js development server.

---

## ✨ Features

- **Solana CNFT Minting**: Leverages the Solana blockchain to mint compressed NFTs (CNFTs).
- **Metadata Upload**: Upload metadata to IPFS via Pinata integration.
- **Web3 Integration**: Built with Solana/Web3 to interact with the blockchain.

---

## 📝 Authors

- Telegram [Immutal0](https://t.me/Immutal0)
- Twitter [Immutal0_](https://x.com/Immutal0_)

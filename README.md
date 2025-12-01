# PHR Vault – Blockchain-Based Personal Health Records (2026 Prototype)

PHR Vault is a decentralized, blockchain-powered Personal Health Record (PHR) system designed to give patients full control over their health data with high security, transparency, and privacy.
This project demonstrates how Web3 technologies (Solidity, IPFS, smart contracts) can improve the security and usability of health data, transforming traditional PHR models into patient-centric systems.

## Key Features

- Decentralized Storage using IPFS
- Smart Contract-Based Access Control
- Patient-Owned Data Model
- Zero Trust Architecture
- Tamper-Proof Medical Records
- Ethereum/Solidity Backend
- React/NextJS Frontend Demo

## Problem Statement

Traditional PHR systems are centralized, vulnerable to breaches, and do not give patients full control.

PHR Vault solves this by using blockchain for:

Verifiable data integrity
- Immutable logging
- Distributed storage
- Transparent consent management

## Tech Stack
- Component	Technology
- Smart Contracts	Solidity (EVM)
- Storage	IPFS
- Frontend	React / Next.js
- Wallet	MetaMask
- Backend	Node.js
- Security	SHA-256 hashing, Access roles

## Architecture Overview
```
Patient ---> React App ---> MetaMask ---> Smart Contract ---> IPFS Storage ###
Provider --> Smart Contract --> Permission Check --> Access Approved/Denied
```

## How It Works

- Patient logs in via Web3 wallet
- Patient uploads encrypted data → stored on IPFS
- Smart contract stores metadata
- Provider requests access
- Patient approves/denies access
- Immutable audit trail recorded on blockchain

## Planned 2026 Release

Zero-Knowledge Proof integration
Multi-chain support (Ethereum/ Polygon / Solana)
Encrypted metadata indexing
HIPAA-aligned architecture

## 👨‍💻 Author

Dr. Sumeet Bajaj
PhD (Blockchain-Based Personal Health Records)
LinkedIn: https://linkedin.com/in/sbajaj5

## License

- MIT License


## Academic Reference

This system is based on the dissertation:
“Blockchain-Based Personal Health Records (PHR): A Patient-Centered Qualitative Analysis”
University of the Cumberlands, 2025

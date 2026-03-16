<h1 align="center">CertifyChain – Blockchain Certificate Verification System</h1>

<p align="center">
A decentralized application (DApp) for issuing and verifying academic certificates using Ethereum blockchain technology.
</p>

---

## Overview

CertifyChain is a blockchain-based certificate management system designed to eliminate certificate fraud and simplify the verification process. Traditional certificate systems rely on centralized databases or paper-based documents, which are vulnerable to tampering, duplication, and manual verification delays.

This project implements a **decentralized certificate issuance and verification system** using **Ethereum smart contracts**. Certificate information is securely stored on the blockchain, ensuring **immutability, transparency, and trust** in digital credentials.

Institutions can issue certificates on-chain, and anyone can verify their authenticity through the decentralized system.

---

## Key Features

* Blockchain-based certificate issuance
* Secure certificate verification using unique certificate IDs
* Immutable storage of certificate records on Ethereum blockchain
* MetaMask wallet authentication
* Transparent and tamper-proof certificate verification
* Smart contract–based certificate management
* Web-based interface for certificate issuance and verification

---

## Technology Stack

### Blockchain

* Ethereum
* Solidity Smart Contracts
* Truffle Framework
* Ganache / Sepolia Network

### Frontend

* React.js
* Web3.js / ethers.js

### Backend

* Node.js
* Express.js

### Authentication

* MetaMask Wallet

---

## Project Architecture

```
User / Institution
        │
        ▼
React Frontend Interface
        │
        ▼
Web3.js / ethers.js
        │
        ▼
Ethereum Smart Contract (Solidity)
        │
        ▼
Ethereum Blockchain Network
```

---

## Core Functionalities

### Certificate Issuance

Authorized institutions can issue new certificates by submitting details such as:

* Certificate ID
* Student Name
* Course Name
* Institution Name
* Issue Date

The certificate data is recorded on the blockchain through a smart contract.

---

### Certificate Verification

Anyone can verify the authenticity of a certificate by entering its **Certificate ID**.
The system retrieves the certificate data directly from the blockchain and displays its verification status.

---

### Certificate Update & Tracking

The system keeps track of certificate updates and maintains the **history of changes** to ensure transparency and accountability.

---

## Smart Contract Capabilities

The smart contract enables the following operations:

* Issue new certificates
* Retrieve certificate information
* Verify certificate authenticity
* Track certificate modification history

These operations ensure that certificate records remain **tamper-proof and transparent**.

---

## Running the Project

Start the local blockchain (Ganache):

```bash
truffle migrate
```

Start the backend server:

```bash
npm start
```

Run the frontend:

```bash
cd certificate-frontend
npm start
```

Make sure **MetaMask** is connected to the correct network.

---

## Applications

* Academic certificate verification
* Digital credential management
* Employer credential verification
* Secure document validation
* Fraud prevention in certification systems

---

## Advantages of Blockchain-Based Certification

* Tamper-proof records
* Decentralized verification
* Increased trust and transparency
* Reduced verification time
* Elimination of fake certificates

---

## Future Improvements

Potential future enhancements include:

* Multi-institution certificate verification network
* Integration with IPFS for decentralized document storage
* QR-based certificate verification
* Mobile application for credential verification
* Integration with global academic verification systems

---

## License

This project is licensed under the **MIT License**.

---

## Acknowledgment

This project was developed as part of a collaborative academic project exploring blockchain-based solutions for secure certificate verification.


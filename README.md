# Healthcare Management System using Blockchain

A decentralized healthcare management system (DApp) built using blockchain technology to securely manage patient records and doctor access. This project ensures data privacy, transparency, and role-based access control using smart contracts on Ethereum.

---

## Project Overview

Traditional healthcare systems store sensitive patient data in centralized servers, making them vulnerable to data breaches, tampering, and unauthorized access.

This project uses blockchain to solve these problems by:

- Storing medical data immutably
- Allowing patients to control who can access their records
- Verifying registered doctors on-chain
- Removing dependency on a central authority

---

## Main Objectives

- Secure storage of patient medical records
- Role-based access control (Doctor / Patient)
- Prevent unauthorized access to sensitive data
- Ensure data integrity and transparency
- Use smart contracts for secure execution

---

## Key Features

### Patient
- Register as a patient
- Control access to personal medical records
- Authorize or revoke doctor access
- View personal health records securely

### Doctor
- Register as a verified doctor
- Add medical records only after patient authorization
- View patient records (if authorized)

### Security
- Blockchain immutability
- Ethereum address-based identity
- Role-based access control using smart contracts
- No centralized database

---

## How It Works

1. User connects wallet using MetaMask
2. Smart contract is loaded from the blockchain
3. Users interact with the DApp based on their role:
   - Patient
   - Doctor
4. All sensitive operations are handled by smart contracts
5. Records are stored on-chain in a tamper-proof manner

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React.js |
| Blockchain | Ethereum |
| Smart Contracts | Solidity |
| Web3 Provider | Web3.js |
| Development Framework | Truffle |
| Local Blockchain | Ganache |
| Wallet | MetaMask |

---

## Project Structure


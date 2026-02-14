# E-Certify:Blockchain-Based Certificate Generation and Verification System

A secure and scalable platform for issuing, storing, and verifying academic certificates using blockchain technology.  
The system ensures integrity, authenticity, and tamper resistance while enabling instant validation by third parties.

---

## Objectives

- Prevent certificate tampering and duplication  
- Provide instant and automated verification  
- Reduce administrative overhead  
- Enable trusted sharing across institutions and employers  

---

## Key Features

- Digital certificate issuance  
- Cryptographic hash generation  
- Immutable blockchain storage  
- QR / ID based validation  
- Role-based access control (Administrator / Student / Verifier)  
- Secure handling of credentials through environment configuration  

---

## System Workflow

1. Administrator inputs candidate and certification details  
2. System generates the certificate  
3. A cryptographic hash is created  
4. Hash is recorded on blockchain  
5. Student receives certificate with verification reference  
6. Verifier recomputes the hash and validates authenticity  

---

## Technology Stack

Frontend: React, Tailwind CSS  
Backend: Node.js, Express  
Database: MongoDB   
Blockchain: Ethereum 

---

## Installation and Setup

```bash
git clone https://github.com/Sanjanakulal/BlockChain-Based-Certification-Generation-and-Verification-System.git
cd project-directory
npm install
npm run dev

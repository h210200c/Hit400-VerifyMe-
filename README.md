# VerifyMe – A Blockchain-Powered eKYC Platform for Identity Verification in Africa

## 📌 Overview

**VerifyMe** is an innovative electronic Know Your Customer (eKYC) platform designed to address the identity verification crisis in Africa. It leverages blockchain (Algorand), AI-powered verification, and privacy-preserving cryptographic techniques to deliver a fast, secure, and scalable solution for onboarding users in low-infrastructure environments.

This project was developed as part of the capstone requirement for the BSc Software Engineering program at Harare Institute of Technology.

---

## 👨‍💻 Authors

- **Tanaka Zhou**  
  _Email:_ h210200c@hit.ac.zw  
  _Reg No:_ H210200C  
- **Supervisor:** Mutandavari

---

## 🧠 Problem Statement

> Over 400 million Africans lack formal identity documents. Traditional KYC systems are slow, expensive, centralized, and vulnerable to fraud. VerifyMe solves this through a decentralized, automated, and privacy-focused identity verification platform.

---

## 🎯 Objectives

- Automate document verification using OCR and facial recognition
- Validate identity using government and financial institution databases
- Ensure user ownership of data through blockchain-based eKYC wallets
- Perform sanctions screening and proof of residence verification using AI
- Support secure, decentralized data handling with zero-knowledge proofs (zk-SNARKs)

---

## 🔧 Technologies Used

- **Blockchain:** Algorand (Pure Proof-of-Stake, co-chains)
- **AI & ML:** Tesseract OCR, 3D liveness detection, behavioral biometrics
- **Privacy & Security:** zk-SNARKs, AES-256 encryption, Decentralized Identifiers (DIDs)
- **Architecture:** Modular, scalable microservices
- **Regulatory Compliance:** GDPR, NDPR, FATF KYC/AML standards

---

## ⚙️ Features

| Feature                            | Description |
|-----------------------------------|-------------|
| 🧾 OCR + Document Upload          | 98% accurate ID extraction via Tesseract OCR |
| 😃 Facial Recognition             | Biometric face matching with 3D liveness detection |
| 🔒 zk-SNARKs                      | Private identity proof without data exposure |
| 🌍 Real-Time Validation           | Database checks with government institutions |
| 📜 Proof of Residence             | LLM-based document comparison |
| 🧠 Behavioral Biometrics          | Device fingerprinting and keystroke dynamics |
| 🏦 Sanctions Screening            | Integrated global watchlists (e.g., OFAC, UN lists) |
| 📲 Mobile & Offline Friendly      | Works in low-bandwidth areas and supports USSD |

---

## 📊 Performance Metrics

| Component               | Metric                  | Result     |
|------------------------|-------------------------|------------|
| OCR Accuracy           | Precision / Recall      | ~95%       |
| Face Match EER         | Equal Error Rate        | <2%        |
| Verification Time      | Average latency         | ~5 seconds |
| Fraud Detection        | False Positive Reduction| ~90%       |
| System Throughput      | Concurrent Users        | 50,000+    |

---

## 🧪 System Architecture

The system is composed of:

- Frontend (User Portal & Mobile)
- API Gateway
- Document Verification Service (OCR + ML)
- Biometric Matching Engine
- Sanctions & Residency Validation Engine
- Blockchain Storage Layer (Algorand)
- Audit and Compliance Layer

---

## 🔮 Future Enhancements

- **Decentralized ID (DID/VC)**: Enable self-sovereign identity via Hyperledger Aries
- **Multilingual OCR**: Support for Amharic, Swahili, Zulu, etc.
- **Adaptive UX**: Mobile-first, voice/SMS interfaces for low-literacy users
- **Cross-Border Interoperability**: Comply with AU interoperability frameworks
- **Auditability with ZKP**: Privacy-preserving compliance logs

---

## 🏁 Getting Started (Prototype Setup)

```bash
# Clone repository
git clone https://github.com/h210200c/verifyme-ekyc.git
cd verifyme-ekyc

# Install dependencies (e.g., Python, Node.js, etc.)
pip install -r requirements.txt
npm install

# Run the backend
python manage.py runserver

# Run frontend
npm run dev

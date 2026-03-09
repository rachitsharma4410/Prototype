# Prototype
Prototype Code

AetherVote: Sovereign Biometric-Blockchain Voting Infrastructure 🇮🇳

Team: Wild Smashers

Event: India Innovates 2026 - World's Largest Civic Tech Hackathon

Domain: Digital Democracy (Secure E-Voting System)

📖 Overview

AetherVote is a next-generation electoral infrastructure designed to solve the Black Box Paradox of traditional Electronic Voting Machines (EVMs) and eliminate Geographical Disenfranchisement.

By transforming static EVMs into Smart Edge Nodes, AetherVote integrates Aadhaar Biometric Authentication, Zero-Knowledge Proofs (ZKPs), and Ethereum L2 Blockchain technology to allow any Indian citizen to securely vote for their home constituency from any polling booth in the country.

🎯 Core Problem Addressed

Current electoral systems face critical challenges:

Millions Disenfranchised: Migrants and students cannot vote when away from their home constituencies.

Identity Fraud: Double voting and impersonation persist.

Trust Deficit: EVMs are not mathematically verifiable by the public.

Logistical Nightmare: Billions are spent on secure transport and paramilitary deployments.

✨ Key Features (The USP)

Location-Agnostic Voting (Dynamic Ballot): Hardware authenticates via UIDAI API, fetches the voter's home constituency, and dynamically displays only their local candidates on an interactive Touch Screen.

Privacy-Preserving ZKP: Verifies voter eligibility (Age, Citizenship, Liveness) against the Aadhaar registry without the hardware ever exposing or storing the actual Aadhaar number.

Homomorphic Encryption: Utilizes the Paillier Cryptosystem to sum encrypted votes. Individual choices are never decrypted; only the final aggregate is revealed.

Digital VVPAT & E2E Verification: Generates an immutable transaction hash on a distributed ledger, providing voters with a mathematically tamper-proof audit trail.

🛠️ Technology Stack (Simulated in Prototype)

Frontend UI/UX: HTML5, CSS3 (Custom ECI-themed variables), Vanilla JavaScript.

Identity/Auth: Simulated UIDAI Aadhaar API v2.5 integration, zk-SNARKs (Semaphore protocol).

Blockchain/Ledger: Simulated Private Ethereum Layer-2.

Cryptography: Simulated Paillier Homomorphic Encryption.

🚀 How to Run the Prototype

This repository contains a standalone, browser-based simulation of the AetherVote Smart Edge Node.

Clone the repository:

git clone [https://github.com/rachitsharma4410/Prototype.git](https://github.com/rachitsharma4410/Prototype.git)


Navigate to the project directory.

Simply open AetherVote_Prototype.html in any modern web browser (Chrome, Firefox, Safari, Edge). No local server or build tools are required for this frontend simulation.

💻 Usage Guide (Hackathon Demo)

Consent & Boot: Check the "Aadhaar Consent" box to activate the biometric scanner.

Scan: Click the large fingerprint icon to simulate a live biometric scan. The system will simulate the ZKP generation and Aadhaar API handshake.

Dynamic Routing: Watch as the system identifies a mock voter (e.g., from Varanasi) and pulls the specific ballot for that constituency dynamically.

Cast Vote: Select a candidate and click the blue ECI-style vote button.

Audit Trail: Observe the generation of the Digital VVPAT slip and the simulated Ethereum Transaction Hash confirming the End-to-End Encryption.

📜 References & Research

Paillier, P. (1999). "Public-Key Cryptosystems Based on Composite Degree Residuosity Classes" (EUROCRYPT).

UIDAI Aadhaar Authentication API Specification (v2.5).

Developed with ❤️ by Team Wild Smashers for India Innovates 2026.

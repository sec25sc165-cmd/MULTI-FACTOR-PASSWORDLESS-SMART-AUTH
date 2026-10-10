# 🛡️ MPSA — Multi-Factor Passwordless Smart Authentication

An interactive, non-functional web prototype demonstrating **MPSA**, a zero-trust passwordless authentication framework designed to make digital access secure, simple, and affordable without relying on traditional passwords or costly hardware tokens.

---

## 🎯 Problem Statement
- **Password Vulnerabilities**: Traditional passwords are susceptible to phishing attacks, credential stuffing, and reuse across services.
- **Reset Overhead**: Password resets waste time and create high support costs for organizations.
- **Token Expenses**: Advanced hardware security keys are often too expensive for small-to-medium entities[cite: 1].
- **OTP Flaws**: Text-based OTPs are vulnerable to SIM-swapping and social engineering[cite: 1].

---

## 🚀 The MPSA Solution
MPSA replaces traditional credentials by leveraging a user's existing device, local biometric checks, and server cryptographic challenge-responses[cite: 1]:
1. **Trusted Device Binding**: Cryptographic key pair generation tied to device hardware[cite: 1].
2. **Local Biometric/PIN Verification**: Confirms identity locally without sending biometric data over the web[cite: 1].
3. **Server Cryptographic Challenge**: Validates public/private key signatures per session[cite: 1].
4. **Adaptive Risk Checks**: Evaluates contextual signals (IP, device posture) and requests step-up verification for high-risk attempts[cite: 1].

---

## 🛠️ Technology Stack
- **Frontend**: HTML5, CSS3 (Glassmorphism & Cyberpunk CSS Grid), Vanilla JavaScript
- **Background Engine**: HTML5 Canvas Network Animation
- **Standards & Protocols Emulated**: WebAuthn, FIDO2, Passkey Standards, Public-Key Cryptography[cite: 1]

---

## 📁 Repository Structure
```text
├── index.html        # Main prototype file containing HTML structure, cyber styles, and logic
└── README.md         # Project documentation and presentation guide

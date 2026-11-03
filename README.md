# ⚡ SINDU UJWALA YASARAPU

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D9FF&center=true&vCenter=true&width=750&lines=Cybersecurity+Graduate;Digital+Forensics+Learner;Blockchain+%26+Identity+Security;Building+Secure+Digital+Systems" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/FOCUS-CYBERSECURITY-00D9FF?style=for-the-badge&labelColor=000000"/>
  <img src="https://img.shields.io/badge/INTEREST-DIGITAL_FORENSICS-00D9FF?style=for-the-badge&labelColor=000000"/>
  <img src="https://img.shields.io/badge/STATUS-OPEN_TO_ROLES-00FF9C?style=for-the-badge&labelColor=000000"/>
</p>

<p align="center">
  <a href="#-about-me">ABOUT</a> •
  <a href="#-featured-project">PROJECT</a> •
  <a href="#-technical-skills">SKILLS</a> •
  <a href="#-learning-lab">LEARNING</a> •
  <a href="#-connect">CONNECT</a>
</p>

---

## `01 // ABOUT ME`

M.Tech graduate in **Cyber Forensics & Information Security** (JNTU Hyderabad, 2025–26). I like understanding how digital systems work, finding where they break, and building privacy-focused security solutions.

**Areas of interest**
- 🔐 Applied Cryptography
- 🛡️ SOC and Security Monitoring
- 🕵️ Digital Forensics & Incident Response
- ⛓️ Blockchain & Smart Contract Security
- 🪪 Digital Identity & Authentication

`LEARN → BUILD → TEST → INVESTIGATE → SECURE`

---

## `02 // FEATURED PROJECT`

# 🔑 TRUSTID
### Secure Mobile e-KYC | M.Tech Thesis Project

A mobile e-KYC app where users own their digital identity and control who can access their documents.

| Security Component | Implementation |
| --- | --- |
| Digital Identity | Decentralized Identifiers (DIDs) |
| Key Generation | Ed25519 |
| Key Storage | Expo SecureStore |
| Document Encryption | AES-256-CBC (random IV per file) |
| Decentralized Storage | IPFS via Pinata (encrypted files only) |
| Integrity Hashing | Keccak-256 (DID + CID) |
| Smart Contracts | Solidity on Hardhat (local network) |
| Access Control | Consent management, temporary session tokens, audit logs |
| Privacy-Preserving Verification | Circom / Groth16 age proof |

<details>
<summary><b>How it works</b></summary>

1. **Identity:** the app generates an Ed25519 key pair and a DID, and stores them in the device's secure storage.
2. **Encryption and storage:** the backend encrypts each document with AES-256-CBC and uploads only the encrypted file to IPFS. Pinata handles storage and pinning, not encryption.
3. **Integrity:** a Keccak-256 hash of the DID and CID is recorded on-chain through a Solidity contract. No document data goes on the blockchain.
4. **Consent:** users grant, deny, or revoke organization requests. Access happens through expiring session tokens, and every action is logged.
5. **Zero-knowledge verification:** OCR extracts the date of birth, and a Groth16 proof confirms the age condition without revealing the full document to the verifier.

</details>

**Stack:** `React Native` `Node.js` `Express.js` `Solidity` `Hardhat` `Ethers.js` `IPFS` `Pinata` `Circom` `SnarkJS` `Tesseract OCR`

<p align="center">
  <img src="https://img.shields.io/badge/PROJECT_REPOSITORY-COMING_SOON-00D9FF?style=for-the-badge&logo=github&logoColor=00D9FF&labelColor=000000"/>
</p>

---

## `03 // TECHNICAL SKILLS`

**🔐 Security and cryptography**

![Cryptography](https://img.shields.io/badge/Applied_Cryptography-00D9FF?style=flat-square&labelColor=000000)
![ZKP](https://img.shields.io/badge/Zero--Knowledge_Proofs-00D9FF?style=flat-square&labelColor=000000)
![Access Control](https://img.shields.io/badge/Access_Control-00D9FF?style=flat-square&labelColor=000000)
![Forensics](https://img.shields.io/badge/Digital_Forensics_(Academic)-00D9FF?style=flat-square&labelColor=000000)

**💻 Development**

![](https://skillicons.dev/icons?i=javascript,nodejs,express,react)

**⛓️ Blockchain**

![](https://skillicons.dev/icons?i=solidity,ethereum)
![IPFS](https://img.shields.io/badge/IPFS-00D9FF?style=flat-square&logo=ipfs&labelColor=000000)

**🛠️ Tools**

![](https://skillicons.dev/icons?i=git,github,vscode)

---

## `04 // LEARNING LAB`

```bash
┌──(sindu㉿cyber-space)-[~/learning]
└─$ cat current_objectives.txt

[+] SOC Operations and SIEM
[+] Security Alert Investigation
[+] Network Traffic Analysis (Wireshark)
[+] Digital Forensics & Incident Response
[+] Python Security Automation
[+] Application and Blockchain Security
```

---

## `05 // CONNECT`

<p align="center">
  <a href="YOUR_LINKEDIN_URL"><img src="https://img.shields.io/badge/LINKEDIN-00D9FF?style=for-the-badge&logo=linkedin&logoColor=black&labelColor=000000"/></a>
  <a href="mailto:sinduyasarapu321@gmail.com"><img src="https://img.shields.io/badge/EMAIL-00D9FF?style=for-the-badge&logo=gmail&logoColor=black&labelColor=000000"/></a>
</p>

<p align="center"><sub>Open to entry-level roles in security analysis, SOC, DFIR, and blockchain/application security.</sub></p>

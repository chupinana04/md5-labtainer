# Cryptography Security Lab Development on Labtainer

## Overview
This repository contains academic cryptography security labs developed on the **Labtainer** platform for educational purposes.  
The project aims to help students understand **real-world weaknesses of cryptographic hash functions**, particularly MD5, through hands-on experimentation in isolated lab environments.

All labs are designed strictly for **learning, research, and defensive security education**.

---

## Objectives
- Demonstrate practical weaknesses of legacy hash functions
- Help students understand the security implications of hash collisions
- Provide hands-on experience with cryptographic concepts in a controlled environment
- Encourage secure cryptographic design choices

---

## Lab Contents

### 1. MD5 Hash Collision Demonstration
- Students generate or analyze two different files producing the same MD5 hash
- Observe how hash collisions violate data integrity assumptions
- Compare file contents despite identical hash values
- Discuss why MD5 is considered cryptographically broken

### 2. MD5 Collision Attack on RSA Digital Signatures
- Simulate an attack scenario where MD5 is used in RSA digital signatures
- Demonstrate how a valid signature can be reused for different contents
- Illustrate integrity bypass risks when weak hash functions are applied
- Reinforce best practices for secure digital signature schemes

---
## Environment
- Platform: **Labtainer**
- Operating System: Linux
- Tools and Languages:
  - Python
  - OpenSSL
  - Standard Linux command-line utilities

All experiments are conducted in **isolated virtual lab environments**.

---


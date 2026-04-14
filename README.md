# CIA Triad & Cryptography notes for Cybersecurity
Comprehensive cybersecurity notes covering the CIA Triad and Cryptography, including core principles like confidentiality, integrity, availability, encryption techniques, hashing, and practical security applications.

# 🔐 Cybersecurity Fundamentals: CIA Triad & Cryptography

---

## 📌 Table of Contents
- [CIA Triad](#-cia-triad)
- [Confidentiality](#-1-confidentiality)
- [Integrity](#-2-integrity)
- [Availability](#-3-availability)
- [Cryptography](#-cryptography)
- [Types of Cryptography](#-types-of-cryptography)
- [Encryption vs Hashing vs Encoding](#-encryption-vs-hashing-vs-encoding)
- [Common Algorithms](#-common-algorithms)
- [Real-World Applications](#-real-world-applications)

---

# 🛡️ CIA TRIAD

The **CIA Triad** is a fundamental model in cybersecurity that helps protect data and systems.

### 🔺 It stands for:
- **C → Confidentiality**
- **I → Integrity**
- **A → Availability**

These three principles ensure that data is:
- Secure from unauthorized access
- Accurate and trustworthy
- Accessible when needed

---

## 🔐 1. Confidentiality

### 📖 Definition:
Confidentiality ensures that sensitive information is accessed **only by authorized users**.

### 🎯 Objectives:
- Protect data from unauthorized access
- Maintain privacy

### 🔧 Methods:
- Encryption (AES, RSA)
- Authentication (Passwords, Biometrics)
- Access Control (RBAC, ACL)
- Data masking

### 💡 Examples:
- Logging into accounts with passwords
- Secure browsing using HTTPS

---

## 🧾 2. Integrity

### 📖 Definition:
Integrity ensures that data remains **accurate and unaltered** unless modified by authorized users.

### 🎯 Objectives:
- Prevent unauthorized data modification
- Maintain trustworthiness

### 🔧 Methods:
- Hashing (SHA-256, MD5)
- Digital Signatures
- Checksums

### 💡 Examples:
- File verification using hash values
- Detecting tampered data

---

## ⚡ 3. Availability

### 📖 Definition:
Availability ensures that systems and data are **accessible whenever needed**.

### 🎯 Objectives:
- Reduce downtime
- Ensure reliability

### 🔧 Methods:
- Backups
- Load balancing
- Redundancy (Failover systems)
- DDoS protection

### 💡 Examples:
- 24/7 cloud services
- Disaster recovery systems

---

## 🧠 Summary Table

| Principle        | Focus                  | Example              |
|-----------------|-----------------------|----------------------|
| Confidentiality | Prevent data leaks     | Password login       |
| Integrity       | Prevent data tampering | Hash verification    |
| Availability    | Ensure access          | Server uptime        |

---

# 🔑 CRYPTOGRAPHY

## 📖 What is Cryptography?

Cryptography is the process of securing information by converting it into an unreadable format to prevent unauthorized access.

---

## 🔄 Basic Terms

- **Plaintext** → Original readable data  
- **Ciphertext** → Encrypted unreadable data  
- **Encryption** → Plaintext → Ciphertext  
- **Decryption** → Ciphertext → Plaintext  

---

## 🔐 Types of Cryptography

### 🔸 1. Symmetric Key Cryptography

Uses a **single key** for both encryption and decryption.

#### Examples:
- AES
- DES

#### Advantages:
- Fast
- Efficient for large data

#### Disadvantages:
- Key sharing problem

---

### 🔸 2. Asymmetric Key Cryptography

Uses **two keys**:
- Public Key (for encryption)
- Private Key (for decryption)

#### Examples:
- RSA
- ECC

#### Advantages:
- Secure key exchange

#### Disadvantages:
- Slower than symmetric encryption

---

### 🔸 3. Hashing

A **one-way function** that cannot be reversed.

#### Examples:
- SHA-256
- MD5 (not secure)

#### Uses:
- Password storage
- Data integrity verification

---

## 🔍 Encryption vs Hashing vs Encoding

| Feature       | Encryption | Hashing | Encoding |
|--------------|------------|---------|----------|
| Reversible   | Yes        | No      | Yes      |
| Purpose      | Security   | Integrity | Formatting |
| Examples     | AES, RSA   | SHA-256 | Base64   |

---

## 🔐 Common Algorithms

### 🔸 AES (Advanced Encryption Standard)
- Symmetric encryption
- Highly secure and widely used

### 🔸 RSA
- Asymmetric encryption
- Used in secure communication

### 🔸 SHA-256
- Hashing algorithm
- Used for data integrity and passwords

---

## 🌍 Real-World Applications

- **HTTPS (SSL/TLS)** → Secure web browsing  
- **VPNs** → Secure communication  
- **Password Storage** → Hashing + Salting  
- **Digital Signatures** → Authentication and integrity  

---

## 🚀 Final Notes

- Use strong encryption standards like **AES and RSA**
- Avoid outdated algorithms like **MD5 and DES**
- Combine multiple security techniques for better protection

---
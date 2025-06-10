# Stage 20: Security and Cryptography (Projects 369-384)

**Learning Goal**: Implement security measures

## C33: **Hash Function SHA-256**

- **Description**: Implement SHA-256 showing: message padding, block processing, compression function, round operations, final hash generation, and test vector verification.
- **Prerequisites**: UB67, LB46
- **New Concept**: Cryptographic hashing

## C34: **MD5 Implementation Basic**

- **Description**: Build MD5 hasher for learning: round functions, message schedule, initialization vectors, collision demonstration, and why MD5 is deprecated.
- **Prerequisites**: C33
- **New Concept**: Hash algorithms

## C35: **AES Encryption Core**

- **Description**: Create AES-128 implementation: key expansion, SubBytes/ShiftRows, MixColumns operation, round structure, ECB mode, and decryption process.
- **Prerequisites**: C33, TB65
- **New Concept**: Symmetric encryption

## C36: **XOR Cipher System**

- **Description**: Develop XOR encryption: key generation, stream cipher concepts, one-time pad demonstration, key reuse problems, and perfect secrecy discussion.
- **Prerequisites**: LB40, C35
- **New Concept**: Stream ciphers

## C37: **RSA Algorithm Basics**

- **Description**: Implement simple RSA: prime generation (small), key pair creation, encryption/decryption, digital signatures, and padding concepts (simplified).
- **Prerequisites**: UB17, C35
- **New Concept**: Asymmetric crypto

## C38: **Digital Signature Demo**

- **Description**: Build signature system: hash-then-sign approach, signature generation, verification process, tampering detection, and non-repudiation demonstration.
- **Prerequisites**: C37, C33
- **New Concept**: Digital signatures

## C39: **Random Number Security**

- **Description**: Create secure RNG: entropy sources, PRNG algorithms, seed management, statistical tests, and comparison with rand().
- **Prerequisites**: TB31, C36
- **New Concept**: Secure randomness

## C40: **Password Hashing System**

- **Description**: Implement password security: salt generation, bcrypt concepts (simplified), iteration counts, rainbow table defense, and timing attack prevention.
- **Prerequisites**: C33, C39
- **New Concept**: Password security

## C41: **Buffer Overflow Protection**

- **Description**: Build overflow defenses: stack canaries, bounds checking, ASLR concepts, NX bit simulation, and safe string functions.
- **Prerequisites**: MB16, UB47
- **New Concept**: Memory protection

## C42: **Input Sanitization Suite**

- **Description**: Create input validators preventing: SQL injection (simulated), command injection, path traversal, format string bugs, and integer overflow.
- **Prerequisites**: LB35, C41
- **New Concept**: Input validation

## C43: **Access Control Framework**

- **Description**: Develop access system: user authentication, role-based access, permission checking, session management, and audit logging.
- **Prerequisites**: C40, MB40
- **New Concept**: Access control

## C44: **Secure Communication Channel**

- **Description**: Build secure channel: key exchange simulation, message encryption, integrity checking, replay attack prevention, and perfect forward secrecy concepts.
- **Prerequisites**: C37, C8
- **New Concept**: Secure protocols

## C45: **Certificate Validator**

- **Description**: Implement cert checking: certificate parsing (basic), signature verification, chain validation concepts, expiry checking, and trust store usage.
- **Prerequisites**: C38, LB56
- **New Concept**: PKI basics

## C46: **Security Audit Toolkit**

- **Description**: Create security scanner: weak password detection, permission checker, sensitive data finder, configuration auditor, and vulnerability reporter.
- **Prerequisites**: C42, MB45
- **New Concept**: Security auditing

## C47: **Cryptographic MAC**

- **Description**: Build HMAC implementation: key padding, inner/outer hash, message authentication, verification process, and timing-safe comparison.
- **Prerequisites**: C33, C44
- **New Concept**: Message authentication

## C48: **TEST: Secure File Vault**

- **Description**: Create encrypted storage with: master password system, AES file encryption, secure key derivation, integrity verification, secure deletion, access logging, tamper detection, and backup/recovery features.
- **Prerequisites**: C33-C47
- **New Concept**: Security integration

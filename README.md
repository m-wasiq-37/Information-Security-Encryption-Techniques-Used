# Information-Security-Encryption-Techniques-Used

# Encryption Techniques Used

## Overview
This project implements multiple encryption techniques to secure user input text. Each method follows a different approach to transforming plain text into ciphertext, ranging from simple substitution to modern cryptographic standards.

---

![Uploading image.png…]()


## 1. Caesar Cipher

### Description
The Caesar Cipher is one of the simplest and oldest encryption techniques. It is a substitution cipher where each letter in the plaintext is shifted by a fixed number of positions in the alphabet.

### How It Works
- Each character is shifted by a predefined value
- For example, with a shift of 3:
  - A becomes D
  - B becomes E
- Non-alphabet characters remain unchanged

### Example
Plain Text: HELLO  
Encrypted: KHOOR

### Characteristics
- Easy to implement
- Low security
- Vulnerable to brute force attacks

---

## 2. AES (Advanced Encryption Standard)

### Description
AES is a modern symmetric encryption algorithm widely used for secure data encryption. It operates on fixed-size blocks and uses a secret key for both encryption and decryption.

### How It Works
- A random 128-bit key is generated
- The plaintext is encrypted using AES in EAX mode
- The output includes:
  - Encryption key
  - Nonce
  - Ciphertext

### Characteristics
- Highly secure
- Used in real-world applications
- Requires key management for decryption

---

## 3. Base64 Encoding

### Description
Base64 is not a true encryption method but an encoding technique used to convert binary data into a text format.

### How It Works
- Converts input text into bytes
- Encodes bytes into Base64 representation
- Often used for data transmission

### Example
Plain Text: hello  
Encoded: aGVsbG8=

### Characteristics
- Not secure
- Easily reversible
- Useful for data formatting and transfer

---

## Comparison

| Method          | Type           | Security Level | Reversible | Use Case                    |
|----------------|----------------|----------------|------------|-----------------------------|
| Caesar Cipher  | Substitution   | Low            | Yes        | Learning and demonstration  |
| AES            | Symmetric Key  | High           | Yes        | Secure communication        |
| Base64         | Encoding       | None           | Yes        | Data representation         |

---

## Conclusion
This project demonstrates both classical and modern approaches to data transformation and encryption. While Caesar Cipher provides a basic understanding of encryption concepts, AES represents strong, industry-standard security. Base64 is included to illustrate encoding techniques commonly used in web applications.

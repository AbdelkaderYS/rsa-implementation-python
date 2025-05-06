# RSA Cryptography Implementation Exercise

This notebook guides you through implementing RSA cryptography algorithms in Python.

---

## Task 1: Decrypt an RSA-encrypted message

- Use the provided public key parameters to decrypt a message.
- Convert the numerical output to text using the character mapping.

---

## Task 2: Build a complete RSA system with 600-digit safe primes

- Implement the **Strong Pseudoprimality Test** for primality testing.
- Generate **safe primes** (where `p` is prime and `(p - 1) / 2` is also prime).
- Create **RSA encryption and decryption functions**.
- Demonstrate functionality with a sample message.

---

### Important Note

Generating 600-digit safe primes (Task 2) requires significant computation time (potentially **hours**, depending on your hardware).  
For testing and development purposes, consider reducing the bit length to **128** or **256 bits**.

---

**Reference**:  
Joachim von zur Gathen – *CryptoSchool*, Springer (2015)

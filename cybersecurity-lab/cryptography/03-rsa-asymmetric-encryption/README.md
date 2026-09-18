# RSA Asymmetric Encryption

```bash
openssl genrsa -out private-key.pem 2048
openssl rsa -in private-key.pem -pubout -out public-key.pem
openssl pkeyutl -encrypt -in plaintext.txt -out ciphertext -inkey public-key.pem -pubin
openssl pkeyutl -decrypt -in ciphertext -inkey private-key.pem -out decrypted.txt
```

**Concept:** The public key can be shared; the private key must remain secret.

Never upload private keys to GitHub.

- [ ] Completed
- [ ] Documented

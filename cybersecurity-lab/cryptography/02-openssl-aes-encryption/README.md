# OpenSSL AES Encryption

```bash
openssl aes-256-cbc -e -in message.txt -out encrypted_message
openssl aes-256-cbc -d -in encrypted_message -out original_message.txt
```

PBKDF2 example:

```bash
openssl aes-256-cbc -pbkdf2 -iter 10000 -e -in message.txt -out encrypted_message
```

- [ ] Completed
- [ ] Documented

# OpenSSL PKI and CSR

```bash
openssl req -new -nodes -newkey rsa:4096 -keyout key.pem -out cert.csr
openssl req -in cert.csr -text -noout
openssl rsa -in key.pem -text -noout
```

- `key.pem`: private key; keep it secret.
- `cert.csr`: Certificate Signing Request.
- A CSR is not yet a certificate.

Never upload private keys or CSRs containing sensitive information.

- [ ] Completed
- [ ] Documented

# John the Ripper Password Audit

Use John the Ripper only against hashes you own or are explicitly authorized to audit.

```bash
john --list=formats | grep -i sha256
john --show hash.txt
```

Never upload real passwords or sensitive hashes.

- [ ] Completed
- [ ] Documented

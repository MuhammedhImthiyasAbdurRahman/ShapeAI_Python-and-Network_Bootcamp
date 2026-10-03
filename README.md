# Python Hashing & Key Derivation Exercises

**Python 3 · hashlib · Standard library**

Three small learning exercises created during the ShapeAI Python and Network Bootcamp with Harsh. They explore message digests, hexadecimal output, random salts and PBKDF2.

## Exercises

| File | What it demonstrates |
| --- | --- |
| `Challange01.py` | MD5 digest of a sample string |
| `Challange02.py` | SHA-256, SHA3-256 and MD5 digests of the same message |
| `Challange03.py` | PBKDF2-HMAC examples using a random 16-byte salt and 100,000 iterations |

## Run locally

Use Python 3 with the standard `hashlib` and `os` modules; no third-party packages are required.

```bash
python3 Challange01.py
python3 Challange02.py
python3 Challange03.py
```

On Windows, use `python` or `py` if `python3` is unavailable. Run the commands from the repository directory.

## Understanding the output

The first two scripts print hexadecimal digests. The third prints derived keys as Python byte strings; its output changes between runs because it generates a fresh salt.

These are educational comparisons. The MD5 examples illustrate a legacy algorithm and should not be treated as a recommended security design. The scripts do not implement a complete password storage or verification system.

## Learning focus

- Encoding strings as bytes before hashing.
- Comparing digest algorithms and output formats.
- Understanding how random salts change derived keys.

## Author & course credit

**Abdur Rahman Imthiyas** · ShapeAI Bootcamp with Harsh

[Portfolio](https://abdurrahmanimthiyas.wordpress.com/) · [LinkedIn](https://www.linkedin.com/in/muhammedh-imthiyas-abdur-rahman-606a4a245)

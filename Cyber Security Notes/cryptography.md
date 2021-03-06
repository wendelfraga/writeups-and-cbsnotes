## Encoding vs Encryption

**Encoding** transforms data into another format using a scheme that is publicly available so that it can easily be reversed.

**Encryption** transforms data into another format in such a way that only specific individual(s) can reverse the transformation.

For Summary -

- **Encoding** is for maintaining data usability and uses schemes that are publicly available.

- **Encryption** is for maintaining data confidentiality and thus the ability to reverse the transformation (keys) are limited to certain people.


## How to know the number of possible hashes for n bits
- ***We can find the possible hashes of a number by using 2^n where n is the number of bits***

- **Hash's Examples:** **[HASHCAT](https://hashcat.net/wiki/doku.php?id=example_hashes)**

## What is rounds in hash context

- A round consists of several processing steps that include substitution, transposition and mixing of the input plaintext to transform it into the final output of ciphertext. AES uses 128-, 192- or 256-bit keys to encrypt and decrypt data.


## Tools 

 - **[Hash Identifier](https://gitlab.com/kalilinux/packages/hash-identifier/-/tree/kali/master)** -> A python script to identify what type of hashes we are handling.

```
wget  https://gitlab.com/kalilinux/packages/hash-identifier/-/raw/kali/master/hash-id.py
```

- Good site to decrypt hashes: **[HASHES.COM](https://hashes.com/en/decrypt/hash)**

## Others 

- **[John Wordlist Rules](https://www.openwall.com/john/doc/RULES.shtml)** -> rules to create and handling wordlists with john.
- **What is Passphrase?** -> A passphrase is similar to a password. However, a password generally refers to something used to authenticate or log into a system. A password generally refers to a secret used to protect an encryption key. Commonly, an actual encryption key is derived from the passphrase and used to encrypt the protected resource.

# Single Columnar Transposition: Keyless Decryption

Encryption and **keyless** decryption of single columnar transposition ciphers, breaking the cipher without any prior knowledge of the key. Done as part of the PES C-ISFCR Summer Internship (Cryptography domain, 2021).

## Published

IEEE SMARTGENCON 2022: [Novel ways of decrypting transposition ciphers](https://ieeexplore.ieee.org/document/10083631)

## What it does

- Encrypts plain text with a single columnar transposition cipher
- Recovers the plain text from ciphertext without the key, using optimization over column permutations and dictionary matching

## Run

```bash
python demo.py
```

Input is read from `input.txt` and results are written to the output files. See `LiteratureSurveyReport` and `Presentation` for the background and method.

## Author

Nikhil Adyapak - [portfolio](https://nikhiladyapak.github.io/)

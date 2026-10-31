# Text Encryptor or Substitution Cipher

A simple Python program that encrypts and decrypts text using a randomly shuffled substitution cipher. Built while learning Python.

## How it works

- Builds a list of characters (letters, digits, punctuation, and space).
- Makes a copy of that list and shuffles it randomly to create the key.
- **Encryption:** each character is swapped for the character at the same position in the shuffled key.
- **Decryption:** does the reverse, mapping each character back using the key.

## Usage

```
python cipher.py
```

1. Enter the text you want to encrypt.
2. The program prints the cipher text.
3. Paste the cipher text back in to decrypt it.

A new random key is generated every time the program runs, so you can only decrypt text during the same run.

## Note

This is a learning project. Substitution ciphers are easy to break with frequency analysis, so don't use this to protect anything important.

## Concepts practiced

Lists, loops, string building, `random.shuffle()`, and `.copy()`.

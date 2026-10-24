# Encryption Algorithm

A Python command-line program that encrypts and decrypts text using three classical ciphers.

## Ciphers included
- **Caesar cipher**: shifts each letter by a fixed number of positions
- **Vigenere cipher**: shifts letters using a repeating keyword
- **Atbash cipher**: replaces each letter with its mirror in the alphabet (A↔Z, B↔Y, ...)

## How it works
1. The program shows a menu of ciphers.
2. You choose a cipher.
3. You choose whether to **encrypt** or **decrypt**.
4. You enter the text and the key.
5. The program applies the chosen cipher and prints the result.

## How to run
1. Install Python 3
2. Download or clone this repository
3. Run: `python "Encryption Algorithm.py"`
4. Follow the on-screen menu

## Example
                                              ENCRYPTION APPLICATION

1. Caesar
2. Atbash
3. Vigenere
4. Exit

Please enter you choice (1-4): 1

Encrypt or decrypt? (e/d): e

Enter text: Hello

Enter key: 3

Result: Khoor


## Features
- Three ciphers in one program
- Encrypt and decrypt modes
- Input validation and error handling
- Non-letter characters are left unchanged

## What I learned
- Working with strings and character logic in Python
- Using functions, loops, and conditionals
- Handling errors and invalid input

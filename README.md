# Classic Cipher Implementations in C

This repository contains implementations of various classical encryption algorithms (ciphers) written in C, including both source code (`.c`) and corresponding compiled executables (`.exe`). 

## 🔐 Ciphers Implemented

| Cipher Name       | File(s)                          | Description                                       |
|-------------------|----------------------------------|---------------------------------------------------|
| Caesar Cipher     | `ceasar.c`, `ceasar.exe`         | Shifts each letter by a fixed number.             |
| Atbash Cipher     | `atbash.c`, `atbash.exe`         | Maps A↔Z, B↔Y, etc.                               |
| August Cipher     | `august.c`, `august.exe`         | A lesser-known substitution cipher.               |
| Affine Cipher     | `affine.c`, `affine.exe`         | A mathematical cipher using modular arithmetic.   |
| Vigenère Cipher   | `vigenere.c`, `vigenere.exe`     | A polyalphabetic substitution cipher.             |
| Gronsfeld Cipher  | `gronsfeld.c`, `gronsfeld.exe`   | Similar to Vigenère but uses numbers 0–9.         |
| Beaufort Cipher   | `beaufort.c`, `beaufort.exe`     | Variant of Vigenère cipher with a reverse tabula. |
| Autoclave Cipher  | `autoclave.c`, `autoclave.exe`   | Also known as Running Key cipher.                 |
| N-gram Operations | `ngram.c`, `ngram.exe`           | Frequency analysis based on n-grams.              |
| Hill Cipher       | `hill.c`, `hill.exe`             | Uses matrix multiplication and modular arithmetic.|
| Rail Fence Cipher | `railfence.c`, `railfence.exe`   | A transposition cipher using zigzag pattern.      |
| Route Cipher      | `route.c`, `route.exe`           | Transposition cipher using a fixed route pattern. |
| Myszkowski Cipher | `myszkowski.c`, `myszkowski.exe` | Repetitive key columnar transposition.            |

> ⚠️ Note: Some cipher names (like "August") may not refer to widely recognized encryption schemes and might be part of a custom or experimental implementation.

---

## 🔧 How to Compile and Run

1. Make sure you have a C compiler like `gcc` installed.
2. Compile using:
   bash
   gcc affine.c -o affine.exe
3. Run the executable:
   ./affine.exe


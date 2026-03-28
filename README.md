# Caesar Cipher

## Description

This project implements the classic **Caesar cipher** — one of the most famous and simple encryption methods. The project is implemented as a Jupyter Notebook containing both theoretical explanations and practical implementation of the algorithm.

**Purpose:** demonstrate how the Caesar cipher encryption and decryption algorithm works for texts in Russian and English.

## Repository Contents

- **`Zad1_1.ipynb`** — main Jupyter Notebook with code and explanations
- **`Original_text.txt`** — original, unencrypted text
- **`Coded_text.txt`** — text after encryption
- **`Decoded_text.txt`** — text after decryption

## Algorithm Implementation

### Supported Alphabets:
- **Latin alphabet**: A-Z (65-90), a-z (97-122) — 26 characters
- **Russian alphabet**: А-Я (1040-1071), а-я (1072-1103) — 32 characters

### Formulas:
- **Encryption**: `E(c) = (c + k) mod n`
- **Decryption**: `D(c) = (c - k) mod n`

where:
- `c` — character position in the alphabet
- `k` — key (shift)
- `n` — alphabet size (26 for Latin, 32 for Russian)

## How to Use

1. Open `Zad1_1.ipynb` in Jupyter Notebook
2. Run the cells in order:
   - First, the cells with `encode`, `decode`, `read_text`, `write_text` functions
   - Then the encryption cell (reads `Original_text.txt` → writes `Coded_text.txt`)
   - Then the decryption cell (reads `Coded_text.txt` → writes `Decoded_text.txt`)
3. Enter the shift key when prompted by the program

## Author
Strenina T.

## Year
2025

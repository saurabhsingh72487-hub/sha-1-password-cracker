# SHA-1 Password Cracker

This project is part of the freeCodeCamp Scientific Computing with Python certification.

## Description

This program attempts to crack SHA-1 hashed passwords using a list of the top 10,000 most common passwords.

It can also check salted passwords by appending and prepending salts from a known salts file.

## Features

- Crack SHA-1 password hashes
- Support for salted hashes
- Uses Python hashlib library
- Returns:
  - the cracked password
  - or `"PASSWORD NOT IN DATABASE"`

## Files

- `password_cracker.py` → main logic
- `main.py` → runs tests
- `test_module.py` → unit tests
- `top-10000-passwords.txt` → password database
- `known-salts.txt` → known salts database

## Usage

Run the program:

```bash
python main.py

# Command-Line-Password-Manager

A secure and minimalist Password Manager built with Python, designed to store, retrieve, and manage passwords directly from the command line. All credentials are encrypted, ensuring user privacy and safety without relying on third-party tools.

🔧 Features:
🔑 Add, retrieve, update, and delete passwords

🧠 Master password protection

🔒 AES / Fernet encryption for stored credentials

🗃️ Secure storage using encrypted local file (JSON/DB)

🖥️ Lightweight and intuitive CLI interface

🔍 Search accounts by name or tag

🛠️ Tech Stack:
Python 3

cryptography library for encryption

getpass for secure input

json / sqlite3 for local storage

argparse / click for CLI enhancements

✅ Use Cases:
Manage your passwords securely in an offline environment

Avoid browser-based or cloud-stored password managers

Learn about cryptography, encryption, and CLI app development in Python

🛡️ Security Notes:
All data is encrypted before saving

Master password is never stored in plaintext

Designed for local/offline use — no internet required

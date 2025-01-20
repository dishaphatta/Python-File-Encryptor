# Python-File-Encryptor
The Python File Encryptor is a secure application for encrypting and decrypting files using cryptographic techniques. It helps protect sensitive information by transforming files into an unreadable format, making it accessible only with a secret key. This project is ideal for personal data security and learning cryptographic concepts.


<img width="604" alt="fileEncrypT" src="https://github.com/user-attachments/assets/d31283f7-03ac-4a5a-bf31-c0f9b1c6f9b9" />



Generate a secure encryption key & Save and load encryption keys for reuse.
Encrypt plain text files into unreadable files.
Decrypt encrypted files back to their original format.

Ease of Use:
Simple command-line interface for encryption and decryption.

Requirements:
Software:-
- Python 3.x (Download Python)

Python Libraries:
Install the required library:
$ pip install cryptography

**How It Works**
Generate a Key:
A key is generated and saved to a file (encryption_key.key)

Encrypt a File:
Use the generated key to encrypt a file (e.g., plain_text.txt → encrypted_file.txt)

Decrypt a File:
Use the same key to decrypt the file back to its original form (encrypted_file.txt → decrypted_file.txt)

**Usage**
Run the Script:

Execute the main.py file from the command line:
$ python main.py

File Encryption and Decryption:
- Place the file to be encrypted (plain_text.txt) in the same directory as main.py
- The script generates an encrypted file (encrypted_file.txt) and decrypts it back to decrypted_file.txt


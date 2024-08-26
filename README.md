
---

# File Encrypter & Decrypter

## Overview
The **File Encrypter & Decrypter** tool allows you to securely encrypt files in a directory and decrypt them using a generated key. This ensures that files remain secure and inaccessible unless decrypted with the correct key. Please note, this program encrypts **files only**, not folders.

## Features
- **File Encryption**: Encrypt any file in the specified directory.
- **Key Generation**: Automatically generates a key (`thekey.key`) for decryption.
- **File Decryption**: Files can only be decrypted using the generated key and the correct secret code.
  
## Encryption Instructions
1. **Run the Encryption Script**: Navigate to the directory where your files are located and run the `kewalhack.py` Python script:
   ```bash
   python kewalhack.py
   ```
2. **Key Generation**: After running the script, all files in the directory will be encrypted, and a file called `thekey.key` will be automatically generated. This key is necessary for decryption.
3. **Important**: Keep `thekey.key` safe. If it is lost, the files cannot be decrypted.

## Decryption Instructions
1. **Run the Decryption Script**: Navigate to the directory with the encrypted files and run the `kewalrelease.py` Python script:
   ```bash
   python kewalrelease.py
   ```
2. **Enter the Secret Code**: When prompted, enter the secret code to decrypt the files. The default code is:
   ```
   kewal1712
   ```
3. **Ensure Key Availability**: Make sure `thekey.key` is present in the same directory as the encrypted files. This key is necessary for successful decryption.
4. **Decryption Completed**: Once the script runs successfully, all previously encrypted files will be decrypted.

## Important Notes
- This tool **only encrypts files**, not folders.
- Losing the `thekey.key` will make the decryption of files impossible.

## Prerequisites
- **Python 3.x** installed.
- Required Python packages, if any, can be installed using:
   ```bash
   pip install -r requirements.txt
   ```
---

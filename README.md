# Enc

Enc is a command-line tool for encrypting and decrypting files and folders using AES encryption. Encrypted files can only be decrypted with the key specified by the user.

## Features

- Encrypt files and folders
- Decrypt encrypted files and folders with the user-specified key

## Usage

To encrypt a file:

enc --encrypt f <file_path>


To encrypt a folder:

enc --encrypt F <folder_path>


To decrypt an encrypted file:

enc --decrypt f <file_path>


To decrypt an encrypted folder:

enc --decrypt F <folder_path>


You will be prompted to enter the encryption/decryption key, which must be at least 16 characters long.

## Example

Encrypt a file:

enc --encrypt f secret.txt


Decrypt the encrypted file:

enc --decrypt f secret.txt


## Note

Make sure to keep your encryption key secure. Once a file or folder is encrypted, it can only be decrypted with the correct key.

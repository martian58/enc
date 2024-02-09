# Enc

Enc is a command-line tool for encrypting and decrypting files and folders using AES encryption. Encrypted files can only be decrypted with the key specified by the user.

## Features

- Encrypt files and folders
- Decrypt encrypted files and folders with the user-specified key

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/martian58/enc.git
cd enc 
chmod +x install_requirements
chmod +x enc
./install_requirements
```

## Usage

To encrypt a file:

```bash
enc --encrypt f <file_path>
```

To encrypt a folder:
```bash
enc --encrypt F <folder_path>
```

To decrypt an encrypted file:
```bash
enc --decrypt f <file_path>
```

To decrypt an encrypted folder:
```bash
enc --decrypt F <folder_path>
```

You will be prompted to enter the encryption/decryption key, which must be at least 16 characters long.

## Example

Encrypt a file:
```bash
enc --encrypt f secret.txt
```

Decrypt the encrypted file:
```bash
enc --decrypt f secret.txt
```

## Note

Make sure to keep your encryption key secure. Once a file or folder is encrypted, it can only be decrypted with the correct key.

## License

This project is licensed under the terms of the GNU General Public License (GPL) version 3. See the LICENSE file for details.
Contributing

If you would like to contribute to VenX, please open an issue or submit a pull request. Your contributions are highly welcome.

## Author

    Fuad Alizada
    Email: fuadelizade6@gmail.com
    GitHub: martian58
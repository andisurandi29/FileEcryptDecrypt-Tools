# File Encryptor/Decryptor

A simple GUI application to encrypt and decrypt files in a folder using AES encryption with password validation.

## Features

- Encrypts files and renames them to random strings.
- Decrypts files and restores their original names.
- Validates the password before decryption.

## Download

You can download the executable file from the [Releases](https://github.com/andisurandi29/FileEcryptDecrypt-Tools/releases) section.

## Usage

1. Download the executable file from the [Releases](https://github.com/andisurandi29/FileEcryptDecrypt-Tools/releases) section.

2. Run the executable file.

3. Select the folder you want to encrypt or decrypt.

4. Choose whether to encrypt or decrypt the folder:
   - **Encrypt**: Enter a password to encrypt all files in the folder. The files will be renamed to random strings and encrypted.
   - **Decrypt**: Enter the same password used for encryption to decrypt the files and restore their original names.

## Notes

- Make sure to remember the password used for encryption. Without it, the files cannot be decrypted.
- The application uses HMAC to ensure the integrity of the encrypted files.

## License

This project is licensed under the MIT License.

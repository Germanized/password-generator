# GermGen

[![Logo](https://i.ibb.co/928s7Xk/GermGen.gif)]

## Overview

This application is a secure and customizable password generator. It allows users to generate passwords with various configurations and ensures their security with AES 256 bit encryption and obfuscated the hell out of it
it's better than dn spys one

## Key Features

- **Customizable Password Length**: Users can specify the length of the generated password.
- **Flexible Character Sets**: The application can include letters, numbers, symbols, Greek and Cyrillic letters, and custom symbols.
- **Encryption**: Passwords are securely encrypted using AES encryption.
- **Password History Management**: Users can save generated passwords and export them for record-keeping.
- **Configurable Settings**: Adjust character set preferences and other settings easily.

## Code Overview

### Key Components

1. **Configuration Management**:
   - The application uses a JSON file (`config.json`) to manage user settings, including which character sets to include.
   - Configuration can be updated dynamically through the application’s menu.

2. **Encryption**:
   - Passwords are encrypted using AES encryption to ensure that they are securely stored.
   - An AES key is generated and stored securely to protect the encrypted data.

3. **Password Generation**:
   - The application generates passwords based on user-defined character sets and length requirements.
   - It supports various character types including letters, numbers, symbols, and user-defined characters.

4. **Password History**:
   - Generated passwords are saved to a history file (`password_history.txt`) in an encrypted format.
   - Users can export this history to a JSON file for review.

5. **User Interface**:
   - A text-based menu allows users to interact with the application, including generating passwords, updating configurations, and viewing help.

### Example Functions

- **`generate_password(length, char_sets)`**: This function creates a password of a specified length using the character sets defined in the configuration.

- **`encrypt_aes(data)`**: Encrypts data using AES encryption to ensure secure storage.

- **`decrypt_aes(encrypted_data)`**: Decrypts encrypted data so that it can be read or used.

- **`update_config(config)`**: Updates the configuration settings based on user input, including character set preferences.

### Security Considerations

- **AES Encryption**: The application uses AES encryption to protect passwords. The encryption key is securely stored and managed.
- **File Permissions**: Sensitive files like encryption keys are protected with appropriate file permissions to prevent unauthorized access.

## Getting Started

1. **Download and Run**: Obtain the executable file and run it on your system.
2. **Configuration**: Adjust settings as needed using the in-app menu.
3. **Generate Passwords**: Use the application to create passwords and manage your password history.

## Troubleshooting

- **File Errors**: Ensure that the application has the necessary permissions to read and write files in its directory.
- **Configuration Issues**: Reset configurations if files are missing or corrupted.

## Credits

Developed by [Germanized](https://germanized.github.io/). All rights reserved.

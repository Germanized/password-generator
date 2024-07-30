# Password Generator

## Overview

its better than dn spy lol use by own 256 bit shit basically uncrackable when obfuscated

## Features

- **Password Length:** Generate passwords ranging from 16 to 10,000 characters.
- **Special Characters:** Include mathematical symbols, Greek letters, Cyrillic letters, and more.
- **Letter Cases:** Support for uppercase and lowercase letters.
- **Numbers:** Optional inclusion of digits.
- **Mathematical Symbols:** Include mathematical symbols for added complexity.
- **Greek Letters:** Option to add Greek letters.
- **Miscellaneous Symbols:** Add additional symbols for enhanced security.
- **Strong Password:** Ensures diverse character types.
- **Password History:** Save passwords with timestamps and optionally export history.
- **Security:** Encrypt and decrypt passwords using AES encryption.

## Installation

1. Clone the repository:
    ```markdown
    git clone https://github.com/Germanized/PasswordGenerator.git
    ```
2. Navigate to the project directory:
    ```markdown
    cd PasswordGenerator
    ```
3. Install the required dependencies:
    ```markdown
    pip install pycryptodome colorama
    ```

## Usage

1. Run the script:
    ```markdown
    python password_generator.py
    ```
2. Choose an option from the menu:
    - **Generate Password:** Create a new password with your chosen settings.
    - **Update Configuration:** Modify the settings for password generation.
    - **Export Password History:** Export the history of generated passwords to a JSON file.
    - **Show Help:** Display information about the tool.
    - **Exit:** Exit the application.
    - **Credits:** View credits for the project.

## Configuration

The configuration file `config.json` allows you to customize the password generation settings:
- **include_numbers:** Whether to include numbers in the password.
- **include_math:** Whether to include mathematical symbols.
- **include_greek:** Whether to include Greek letters.
- **include_misc:** Whether to include miscellaneous symbols.
- **include_cyrillic:** Whether to include Cyrillic letters.
- **custom_symbols:** List of additional custom symbols.

## Security

The tool uses AES encryption to securely store and manage passwords. The encryption key is stored in `keys/aes_key.key` and is protected with file permissions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Credits

Developed by Germanized.

## Contact

For any questions or suggestions, please contact [Germanized](https://github.com/Germanized).


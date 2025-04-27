# PyEncoder 🔒

![PyEncoder](https://img.shields.io/badge/PyEncoder-Obfuscator-blue?style=for-the-badge)

Welcome to **PyEncoder**, a powerful Python script obfuscator designed to enhance the security of your Python files. With PyEncoder, you can encode your `.py` files using advanced techniques like marshal, zlib, and base encodings. This tool supports multi-layer encoding, reverse string obfuscation, and `.pyc` compilation, making it an essential asset for developers looking to protect their code across various platforms, including Windows, Linux, and Termux.

[Download the latest release here!](https://github.com/FTWGaming/Pyencoder/releases)

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Encoding Techniques](#encoding-techniques)
5. [Compatibility](#compatibility)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Features ✨

- **Multi-layer Encoding**: Enhance your script's security with multiple layers of encoding.
- **Reverse String Obfuscation**: Protect sensitive strings within your code.
- **.pyc Compilation**: Compile your scripts into bytecode for additional security.
- **Cross-Platform Support**: Compatible with Windows, Linux, and Termux.
- **Easy to Use**: Simple command-line interface for quick encoding.

## Installation 🛠️

To install PyEncoder, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/FTWGaming/Pyencoder.git
   ```

2. **Navigate to the Directory**:

   ```bash
   cd Pyencoder
   ```

3. **Install Dependencies**:

   Ensure you have Python installed. Use pip to install any required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Script**:

   You can now run the PyEncoder script. Check the usage section for commands.

## Usage 📜

Using PyEncoder is straightforward. Here’s how to encode your Python files:

1. **Basic Encoding Command**:

   ```bash
   python pyencoder.py your_script.py
   ```

   This command will encode `your_script.py` and generate an obfuscated output file.

2. **Multi-layer Encoding**:

   To apply multiple layers of encoding, use the `--layers` option:

   ```bash
   python pyencoder.py your_script.py --layers 3
   ```

3. **Reverse String Obfuscation**:

   If you want to obfuscate specific strings in your code, use the `--obfuscate` option:

   ```bash
   python pyencoder.py your_script.py --obfuscate
   ```

4. **Compiling to .pyc**:

   To compile your script into a `.pyc` file, use the `--compile` option:

   ```bash
   python pyencoder.py your_script.py --compile
   ```

5. **Help Command**:

   For more options, you can always run:

   ```bash
   python pyencoder.py --help
   ```

## Encoding Techniques 🔐

PyEncoder employs several encoding techniques to secure your scripts:

- **Marshal**: This method serializes Python objects, allowing you to store and retrieve them easily.
- **Zlib**: A compression library that reduces the size of your encoded files, making them less readable.
- **Base Encodings**: Using base16, base32, and base64 encodings to further obfuscate your scripts.

Each technique adds a layer of complexity, making it harder for unauthorized users to understand your code.

## Compatibility 🖥️

PyEncoder works seamlessly across different operating systems:

- **Windows**: Fully supported with easy installation.
- **Linux**: Tested on various distributions, ensuring reliable performance.
- **Termux**: Works well on Android devices with Termux installed.

No matter where you are developing, PyEncoder has you covered.

## Contributing 🤝

We welcome contributions from the community. If you would like to help improve PyEncoder, please follow these steps:

1. **Fork the Repository**: Click the "Fork" button on the top right of this page.
2. **Create a New Branch**: Use a descriptive name for your branch.
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Your Changes**: Implement your feature or fix a bug.
4. **Commit Your Changes**: Write clear and concise commit messages.
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to Your Fork**:
   ```bash
   git push origin feature/YourFeature
   ```
6. **Create a Pull Request**: Submit your changes for review.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact 📬

For questions or feedback, please reach out via the following channels:

- **GitHub Issues**: Use the [Issues](https://github.com/FTWGaming/Pyencoder/issues) section for bug reports or feature requests.
- **Email**: You can contact us at support@example.com.

Thank you for checking out PyEncoder! 

For the latest releases, please visit [this link](https://github.com/FTWGaming/Pyencoder/releases) to download and execute the latest version.
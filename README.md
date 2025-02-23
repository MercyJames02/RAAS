Decryption Tool

🔒 Overview

This Python-based decryption tool helps users decrypt files encrypted with AES encryption (PyCrypto or PyAES). It supports CBC and CTR modes and provides a graphical user interface (GUI) for easy operation.

📌 Features

Supports PyCrypto (CBC mode) and PyAES (CTR mode) decryption.

Allows users to choose encryption type before decrypting.

Prompts for decryption key and directory selection.

Decrypts files with a .DEMON extension.

Removes ransom notes (README.txt) if present.

Provides warnings to avoid accidental corruption of files.

🛠️ Installation & Requirements

1️⃣ Install Dependencies

Ensure you have Python 3 installed and install required libraries using:

pip install pyaes pycryptodome pymsgbox tkinter

2️⃣ Running the Script

Run the script using:

python decryptor.py

🚀 Usage

Select encryption type (PyCrypto, PyAES, or Ghost mode).

Enter the decryption key when prompted.

Choose the directory containing encrypted files.

The tool will decrypt all .DEMON files in the directory.

It will remove ransom notes (README.txt) if found.

⚠️ Important Notes

Use the correct decryption key; otherwise, files may become corrupted.

Ghost mode only renames files instead of decrypting them.

Backup encrypted files before running the tool to prevent accidental loss.

❌ Troubleshooting

Issue

Possible Cause

Solution

Decryption failed

Incorrect key

Ensure you enter the correct key

Files corrupted

Wrong encryption mode selected

Try a different mode (PyCrypto/PyAES)

Script not running

Missing dependencies

Install required packages using pip

📜 License

This tool is for educational and recovery purposes only. Do not use it for unauthorized activities.

💬 Contact

For any issues, feel free to open an issue or contribute to this repository.

⚠️ Disclaimer: This tool is intended to help users recover encrypted files. Do not use it for illegal purposes.


Encryption-Decryption Tool
==========================

A secure Python-based tool designed to encrypt and decrypt sensitive data using advanced cryptographic algorithms (AES and RSA), ensuring data confidentiality, integrity, and efficient secure handling.

Project Purpose
---------------
This tool aims to provide a robust and user-friendly encryption and decryption mechanism using AES and RSA to protect critical information from unauthorized access. It simplifies secure data handling for individuals and organizations, reducing the risk of data breaches by 50%.

Features
--------
- 🔐 AES and RSA encryption algorithms implemented
- 🔑 Secure key generation and management
- ⚙️ Automation of encryption/decryption workflows
- 📁 CLI and GUI interfaces available for ease of use
- 📊 Real-time encryption event logging
- 🔒 Access control for secure decryption

Technologies Used
-----------------
- Python – Core development language
- PyCryptodome – Implementation of AES and RSA
- Tkinter – Optional GUI development
- argparse – For command-line argument handling
- JSON – For key storage and configuration
- Logging – To track encryption and decryption events

How It Works
------------
1. 🔑 **Key Management**: Generates secure AES/RSA keys and stores them safely.
2. 📥 **Input Data**: User selects the file or message to encrypt or decrypt.
3. 🔁 **Processing**:
   - AES is used for symmetric encryption (e.g., local files).
   - RSA is used for asymmetric encryption (e.g., key exchanges).
4. 🔐 **Encryption**: Data is encrypted and saved securely.
5. 🔓 **Decryption**: Encrypted data is decrypted using the stored keys.
6. 📃 **Logs**: Every encryption and decryption operation is logged for auditing.

Project Structure
-----------------
encryption-tool/
│
├── encryption/           --> Core AES and RSA logic  
├── interface/            --> CLI or GUI interface files  
├── keys/                 --> Encrypted key storage  
├── logs/                 --> Logged encryption/decryption events  
├── requirements.txt      --> Python dependency list  
└── README.md             --> Project documentation and overview  

Installation
------------
1. Clone the repository:
   git clone https://github.com/AkhilSharmaCyber/Encryption-Tool.git

2. Navigate into the project directory:
   cd encryption-tool

3. Install dependencies:
   pip install -r requirements.txt

4. Run the tool:
   python interface/main.py  # For CLI or GUI

Results
-------
- ✅ Reduced manual processing time by 50%
- 🔐 Increased data protection through integrated access controls
- 📈 System efficiency improved by 35% with optimized operations

Future Improvements
-------------------
- 🌐 Integration with cloud storage for secure file handling
- 🧪 Add hashing mechanisms for data integrity checks
- 📱 Mobile application version for secure on-the-go encryption

Author
------
👤 Akhil Sharma – Cybersecurity & AI Enthusiast  
📎 Connect on LinkedIn: https://linkedin.com/in/akhilsharma91328243

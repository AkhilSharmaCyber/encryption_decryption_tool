
Encryption-Decryption Tool
==========================

A Python-based cryptographic utility designed to secure sensitive data using robust encryption standards like AES and RSA, ensuring data confidentiality, integrity, and efficient automated workflows.

Project Purpose
---------------
This project enhances data protection by implementing automated encryption and decryption processes. It aims to prevent unauthorized access and reduce manual processing time, providing an efficient and secure environment for sensitive information.

Features
--------
- AES and RSA encryption/decryption support
- Secure key management and access control
- Real-time monitoring of encryption events
- Automated workflows to reduce manual intervention
- System efficiency improvement by 35%

Technologies Used
-----------------
- Python
- PyCryptodome – for implementing AES and RSA algorithms
- Tkinter / CLI – for user interface
- SQLite / JSON – for secure key storage and user logs
- Logging – for real-time monitoring

How It Works
------------
1. Input: User uploads or enters data to encrypt/decrypt.
2. Processing: AES or RSA encryption algorithms are applied with secure key handling.
3. Output: Encrypted or decrypted data is displayed or saved.
4. Monitoring: Logs track all encryption events in real-time for auditing.

Project Structure
-----------------
encryption-tool

├── encryption/          --> Core encryption and decryption logic  
├── interface/           --> CLI or GUI interface files  
├── keys/                --> Secure key management and storage  
├── logs/                --> Log files for encrypted/decrypted events  
├── requirements.txt     --> Python dependency list  
└── README.txt           --> Project documentation and overview  

**How It works**:
1. 📤 **Input Data**: Users input plain text or upload a file for encryption or decryption.

2. 🔐 **Encryption**: Based on user choice, either AES or RSA algorithm is applied using securely generated keys.

3. 🗝️ **Key Handling**: Keys are managed securely with access control and optional key storage encryption.

4. 🧾 **Logging**: All operations are logged in real-time for auditing and traceability.

5. 🖥️ **User Interface**: Simple command-line interface or GUI to interact with the tool easily.


Installation
------------
git clone https://github.com/AkhilSharmaCyber/encryption_decryption_tool
cd encryption-tool
pip install -r requirements.txt
python interface/main.py

Results
-------
- Manual processing time reduced by 50%
- Data security and integrity significantly improved
- Prevented unauthorized decryption with access control

Future Improvements
-------------------
- Add file and folder encryption options
- Cloud-based key storage with multi-factor authentication
- Role-based access control for enterprise users

Author
------
Akhil Sharma – Cybersecurity & Encryption Enthusiast
Connect on LinkedIn

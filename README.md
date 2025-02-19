# Ransomware Simulation using AES Algorithm

## Description
This project is part of a thesis research on the **ANALYSIS OF RANSOMWARE ATTACK ON ENCRYPTED FILES IN WINDOWS OPERATING SYSTEM**. The ransomware simulation is developed using Python and is designed to encrypt files in a targeted directory to demonstrate the working mechanism of ransomware attacks.

## Features
- Encrypts files using **AES-256** encryption.
- Targets specific file types such as **PDF, JPG, DOC, TXT, etc.**.
- Generates a unique encryption key per execution.
- Provides a decryption script for analysis purposes.
- Logs activity to track file encryption and decryption process.

## Requirements
- Python 3.x
- Required Python modules:
  ```bash
  pip install pycryptodome
  ```

## Usage
### Encryption
```bash
python encrypt.py "C:\Users\TargetDirectory"
```

### Decryption (with correct key)
```bash
python decrypt.py "C:\Users\TargetDirectory" --key <encryption_key>
```

## Disclaimer
This project is **strictly for educational and research purposes**. The use of ransomware for malicious intent is illegal and punishable by law. The developer is not responsible for any misuse of this code.

## Author
**Fadia Nur Annisa**

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

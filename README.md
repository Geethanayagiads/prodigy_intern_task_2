# prodigy_intern_task_2
# Caesar Cipher Program

This Python program implements the Caesar Cipher encryption and decryption algorithm using Flask for the web interface.

## Features

- **Encryption:** Encrypts plaintext using a specified shift value.
- **Decryption:** Decrypts ciphertext using the reverse shift value.
- **Web Interface:** Utilizes Flask for providing a user-friendly web interface.
- **Interactive Input:** Allows users to input text and select encryption or decryption operations.

## Usage

### Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <prodigy_task_2>
   
2. Install dependencies:
   pip install -r requirements.txt


Running the Program
1. Run the Flask application:
   python caesar_cipher_flask.py

2. Open your web browser and go to http://localhost:5000 to access the Caesar Cipher program.

Example
Encryption:

Input Text: "Hello, World!"
Shift Value: 3
Encrypted Result: "Khoor, Zruog!"
Decryption:

Input Text: "Khoor, Zruog!"
Shift Value: 3
Decrypted Result: "Hello, World!"


Files
caesar_cipher_flask.py: Python script implementing the Caesar Cipher encryption and decryption.
templates/index.html: HTML template for the Flask web interface.


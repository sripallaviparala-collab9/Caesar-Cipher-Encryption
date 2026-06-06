# Caesar-Cipher-Encryption
A Python project that encrypts and decrypts text using the Caesar Cipher algorithm for basic cybersecurity learning.
# Caesar Cipher Encryption

## Overview
This project is a Python implementation of the Caesar Cipher, one of the oldest and simplest encryption techniques in cryptography. The program encrypts a message by shifting each alphabetic character by a user-defined number of positions in the alphabet.

## Features
- Encrypts text using the Caesar Cipher algorithm
- Supports both uppercase and lowercase letters
- Preserves spaces and special characters
- User-defined shift value
- Simple command-line interface

## Technologies Used
- Python 3

## How It Works
The Caesar Cipher works by shifting each letter in a message by a fixed number of positions.

Example:

Input:
```
HELLO
Shift = 3
```

Output:
```
KHOOR
```

## Code Example

```python
message = input("Enter Message: ")
shift = int(input("Enter Shift Value: "))

encrypted = encrypt(message, shift)

print("Encrypted Message:", encrypted)
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Caesar-Cipher-Encryption.git
   ```

2. Open the project folder.

3. Run the Python file:
   ```bash
   python caesar_cipher.py
   ```

4. Enter the message and shift value when prompted.

## Learning Outcomes

- Understanding basic cryptography concepts
- Working with Python functions
- String manipulation techniques
- Character encoding using ASCII values
- Implementing encryption algorithms

## Future Enhancements

- Add decryption functionality
- Support multiple cipher techniques
- Create a graphical user interface (GUI)
- Add file encryption support

## Author

Pallavi Parala

## License

This project is created for educational and learning purposes.

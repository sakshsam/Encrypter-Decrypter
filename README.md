# Encrypter-Decrypter

Tools and Technologies Used:

Python: The project is implemented in Python, a versatile programming language.
Input/Output Handling: The code employs standard input/output for user interaction.
String Manipulation: Utilizes string manipulation for Caesar cipher operations.
Functionality:

Caesar Cipher Encryption: The caesar_cipher_encrypt function encrypts a given plaintext using the Caesar cipher algorithm with a specified shift value.
Caesar Cipher Decryption: The caesar_cipher_decrypt function decrypts a given cipher text using the inverse Caesar cipher with the same shift value.
User Interaction: The main function provides a user-friendly interface for selecting encryption, decryption, or exiting the application.
Features:

Shifted Alphabets: The algorithm shifts alphabets based on the specified shift value, preserving the case of the characters.
Input Validation: The code checks if the characters in the input message are alphabetic before encryption or decryption, ensuring valid processing.
Dynamic User Interaction: The program runs continuously, allowing users to encrypt, decrypt, or exit, providing flexibility.
Important Information:

Limitations: The Caesar cipher is a simple substitution cipher and may not provide robust security for sensitive information.
Educational Purpose: This project is likely designed for educational purposes to understand basic encryption/decryption concepts and user interaction in Python.
Shift Calculation: The shift value is calculated modulo 26 to handle wrapping around the alphabet.
Note: While the Caesar cipher is a classic encryption method, it is not suitable for secure applications. Modern cryptographic algorithms like AES are recommended for sensitive data.

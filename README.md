# CyberSecurityProject
Task 1
Summary of the Project
This project shows a basic Web app for encrypt and decrypt text with they used AeS encryption with a random initial vector(IV). It is a full-blown application that has been crammed into one HTML file by HTML, CSS, JavaScript.

Key Features:
User Interface:

A text field for the message to to be encrypted or decrypted.
A password field for the password
Encryption and decryption Toggles
An output view (encrypted or decrypted text)
Encryption and Decryption:

Uses the CryptoJS library to implement AES encryption.
Creates a random IV for each encryption so that the same plaintext gives a different cipher text each time.
Uses CryptoJS. Then, it uses PBKDF2 to derive an encryption key from the password and IV.
The IV and the encryption combine

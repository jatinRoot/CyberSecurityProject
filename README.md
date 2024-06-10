# CyberSecurityProject
Task 1 Encrypt/Decrypt Text
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



Task 2 Keylogger 

Keylogger Project Summary
What's the Project About?
This project is about creating a simple keylogger—a tool that records every key you press on your keyboard. It's designed to help beginners learn about cybersecurity concepts using basic web technologies like HTML, CSS, and JavaScript.

What Does It Do?
When you type on your keyboard, the keylogger captures each keystroke and displays them in real-time on a webpage. It's like a live feed of everything you're typing, shown directly on your screen.

Key Features:
Real-Time Logging: Instantly shows every key you press.
Sleek Design: Uses a dark theme for a modern, professional look.
Clear Space Key Indicator: Shows [Space] when you press the spacebar.
Scrollable Log Area: Keeps the log organized and easy to read, even if you type a lot.
Technologies Used:
HTML: Structures the webpage.
CSS: Styles the page to look good.
JavaScript: Makes the keylogger work by capturing and displaying keystrokes.
How It Works:
HTML Setup:

The HTML part sets up the basic structure of the page, including a container to display the keystrokes.
CSS Styling:

The CSS part makes everything look nice, with a dark background, light text, and a styled container for the keystroke log.
JavaScript Functionality:

The JavaScript part listens for any keypresses, captures them, and updates the display in real-time. It also handles showing [Space] when the spacebar is pressed.




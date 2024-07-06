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



Task 3 Secure Image Encryption and Decryption Web App for Privacy Protection

Introduction:
Introducing a secure and user-friendly web application that allows you to encrypt and decrypt images using a simple encryption key. This tool is built with HTML, CSS, and JavaScript, ensuring that your images remain safe and secure while being shared online.

How It Works:

1. Upload Image: Simply select an image file from your computer.
2. Enter Key: Provide an encryption key (password) for encrypting and decrypting the image.
3. Encrypt: The app encrypts the image using the key, displaying the encrypted version.
4. Decrypt: Easily decrypt the image back to its original form using the same key.

How to Use:

1. Select an Image: Click on "Choose File" to upload an image.
2. Enter an Encryption Key: Type in a password for encryption.
3. Encrypt the Image: Click "Encrypt" to view the encrypted image.
4. Decrypt the Image: Click "Decrypt" to revert the image to its original form.

Key Features:

* Single Page Application for ease of use
* Responsive Design for compatibility across all devices
* Simple Encryption using XOR operation for efficiency
* Secure: Encrypted image cannot be decrypted without the correct key

Benefits of Using This App:

1. Privacy Protection: Safeguard your images by encrypting them before sharing.
2. User-Friendly: No technical expertise required for encryption and decryption.
3. Efficient Process: Quick and secure encryption and decryption.

Conclusion:
This user-friendly web application provides a simple yet effective way to protect your images with encryption. Start exploring the basics of cybersecurity and cryptography by securely encrypting and decrypting your images today.








Task 4 Web-Based Facial Authentication System Report

The web-based facial authentication system uses HTML, CSS, and JavaScript, leveraging face-api.js for face detection and recognition. The system accesses the webcam to detect faces and display them on a webpage, serving as a foundation for applications such as user authentication in meetings and exams.

Project Setup
The project directory includes index.html and a models folder with pre-trained face-api.js models. The necessary libraries, TensorFlow.js and face-api.js, are loaded via CDN.

HTML and CSS
The HTML file (index.html) contains a video element for the webcam feed. Basic CSS styles center the video on the page.

JavaScript
JavaScript loads face detection models, accesses the webcam, and performs face detection. Detected faces and landmarks are drawn on a canvas overlay.

Running the Application
Start a local server (e.g., python -m http.server).
Access the web app at http://localhost:8000/.
This setup provides a simple and effective facial authentication system.







Task 5 Credit Card Encryption and Decryption

The Credit Card Encryption and Decryption project aims to provide a secure and intuitive web-based application for encrypting and decrypting 16-digit credit card numbers using basic Base64 encoding techniques. Implemented using HTML, CSS, and JavaScript, the application ensures user input validation and clear visual feedback through styled buttons and alert messages.

Implementation Details:

Technologies Used: HTML for structure, CSS for styling, and JavaScript for functionality.
Functionality: Users input a 16-digit credit card number, which is then encrypted and decrypted using simple Base64 encoding methods.
User Experience: Buttons for encryption and decryption are styled in bold blue text for clarity and visual appeal. Alerts prompt users to input valid credit card numbers or perform necessary actions.
This project not only demonstrates foundational web development skills but also emphasizes security principles through access control management and cryptographic techniques, essential in safeguarding sensitive data in digital transactions.

This report encapsulates the project's objectives, technologies used, functionality, user experience, and its significance in reinforcing cybersecurity principles in digital applications.




























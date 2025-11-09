 Task 02 — Image Encryption using Pixel Manipulation

This project demonstrates a simple yet effective approach to image encryption and decryption using pixel-level manipulation in Python. The main goal is to protect image data from unauthorized access by transforming its pixel values into an unreadable form.

⚙ Working Principle
The program loads an image and reads all its pixel values (RGB format).
For encryption, it applies a basic mathematical operation (like addition, subtraction, or XOR) or swaps pixel positions to change the color pattern of the image.
The output is a scrambled image that cannot be visually interpreted.
For decryption, the reverse operation is applied to restore the original image.
💡 Features
Supports both encryption and decryption.
Uses simple pixel manipulation techniques to alter image data.
Demonstrates how cryptography can be applied in image processing.
Provides an educational and ethical way to understand the basics of image security.
🖼 Example Use Case
User selects an image file (e.g., photo.png).
The tool encrypts the image by modifying pixel values.
The encrypted image looks distorted and unreadable.
Running the decryption function restores the original image.

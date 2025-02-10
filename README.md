
Description

This project is a simple implementation of a Steganography tool using Python. Steganography is the practice of concealing a message within another medium, such as an image. This tool allows users to hide text messages within an image and extract the hidden messages from the image. The project uses the stegano library for hiding and revealing messages and the Pillow library for image handling.

Features

Hide text messages within an image.
Extract hidden messages from an image.
User-friendly graphical user interface (GUI) using Tkinter.
Support for PNG and JPG image formats.

Requirements

Python 3.x
Tkinter library (usually included with Python)
Pillow library (Pillow can be installed using pip install pillow)
Stegano library (stegano can be installed using pip install stegano)

Installation

Clone the repository or download the cyber_crime.py file.
Ensure you have Python installed on your system. You can download it from python.org.
Install the required libraries using the following commands:
bashCopy
pip install pillow
pip install stegano

How to Run

Open a terminal or command prompt.
Navigate to the directory where the cyber_crime.py file is located.
Run the following command:
bashCopy
python cyber_crime.py
The GUI will open, allowing you to load an image, hide text messages within it, and extract hidden messages.

Usage

Loading an Image
Click the "Open Image" button to select an image file.
The selected image will be displayed in the left frame.

Hiding a Message

Enter the text message you want to hide in the text area on the right frame.
Click the "Hide Data" button to hide the message within the selected image.
Click the "Save Image" button to save the image with the hidden message.
Extracting a Message
Load the image containing the hidden message using the "Open Image" button.
Click the "Show Data" button to extract the hidden message.
The extracted message will be displayed in the text area on the right frame

Code Structure

showimage(): Opens a file dialog to select an image and displays it in the GUI.
Hide(): Hides the text message within the selected image using the stegano library.
Show(): Extracts the hidden message from the selected image using the stegano library.
save(): Saves the image with the hidden message.



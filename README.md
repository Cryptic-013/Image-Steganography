**Image Steganography Project**

This is a Python project for performing Image Steganography using the Stegano module. The project has two main functions: encoding and decoding an image.


**Requirements**

Before running this project, you need to install the following packages:

    tkinter
    stegano
    You can install them using pip command:

pip install tkinter
pip install stegano

**Usage**

The main file Image_Steganography.py contains two functions, **Encode() and Decode()**, which are called when the respective buttons are pressed.

**Encoding an image**

The **Encode()** function allows you to hide a confidential message inside an image. When you click the "Encode" button, a new window will pop up where you can select the image file and enter the message you want to hide. Then, by clicking the "Encode" button again, the message will be hidden inside the selected image.
Decoding an image

The **Decode()** function allows you to retrieve the hidden message from an image. When you click the "Decode" button, a new window will pop up where you can select the image file that contains the hidden message. Then, by clicking the "Decode" button again, the hidden message will be revealed on the screen.

**Disclaimer**

This code is provided for educational purposes only. The author assumes no responsibility for any illegal or unethical use of this script.

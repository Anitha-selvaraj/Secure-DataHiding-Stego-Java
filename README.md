# Secure Data Hiding in Image Using Steganography  

This Java project implements **image steganography** to securely hide and extract secret messages in images. It ensures confidentiality by making hidden messages invisible to unauthorized users.  

## Features  

- **Hide Data in Plain Sight**: Embeds secret messages inside images using **Least Significant Bit (LSB) steganography** without noticeable changes.  
- **Passcode Protection**: Ensures that only authorized users can retrieve the hidden message.  
- **Lightweight & Fast**: Uses standard Java libraries without extra dependencies.  

## Project Structure  

Secure-DataHiding-Stego-Java/
├── src/
│   ├── Encoder.java
│   ├── Decoder.java
│   ├── Main.java
│
├── images/
│   ├── input.png
│   ├── encryptedImage.png
│
├── README.md

## How to Run  

1. **Place an image** in the `images/` folder and rename it as `input.png`.  
2. **Compile and run the program** using:  

   ```sh
   javac src/*.java
   java src.Main
   ```

3. **Enter the secret message and passcode** when prompted.  
4. **To decrypt**, provide the correct passcode to retrieve the hidden message.  

## Requirements  

- Java 8 or later  
- PNG image format for encoding and decoding  

## Future Enhancements  

- **Encryption Integration**: Encrypt messages before embedding for added security.  
- **Multi-Format Support**: Extend compatibility to JPEG, BMP, and other image formats.  
- **Advanced Security Techniques**: Enhance steganography methods for better protection.  
- **Machine Learning Integration**: Detect and improve hidden message encoding.  

---

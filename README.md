# **Steganography Image Encoder & Decoder**  

This Python project hides and retrieves secret messages in images using **LSB (Least Significant Bit) steganography**.  

## **Features**  
✅ Hide a secret message in an image  
✅ Password-protected decryption  
✅ Simple command-line interface  

## **Setup & Usage**  

### **Installation**  
Ensure you have Python installed, then install OpenCV:  
```bash
pip install opencv-python
```

### **Encoding a Message**  
1. Place your image as **stego_image.png** in the project folder.  
2. Run:  
   ```bash
   python stego.py
   ```  
3. Enter your secret message and a passcode.  
4. The encoded image is saved as **encryptedImage.jpg**.  

### **Decoding a Message**  
1. Run the script and enter the correct passcode.  
2. If the passcode is correct, the hidden message is revealed.  

## **Requirements**  
- Python 3.x  
- OpenCV (`cv2`)  

## **License**  
MIT License  

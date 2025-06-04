# 🖼️ Image Encryption Tool (Pixel Manipulation)

A beginner-friendly image encryption and decryption tool using pixel value transformation and shuffling — built in Python.

## 🔐 Features

- Encrypts pixel values using modular math
- Scrambles pixel positions with a key-based seed
- Restores original image with correct key + seed
- Supports `.png`, `.jpg`, `.bmp`

## 📦 Dependencies

```bash
pip install pillow numpy matplotlib
python Num.py

## A dialog will prompt you to select an image. 
The image will be:

Displayed

Encrypted (value-based)

Shuffled (position-based)

Decrypted and restored

## 🧠 How It Works
Adds a numeric key to each pixel value using modulo 256

Randomly shuffles pixel positions using a NumPy seed

Decrypts by reversing both transformations

## 📁 Output Files
encrypted.png: Value encrypted

shuffled.png: Value + position encrypted

decrypted.png: Final restored image

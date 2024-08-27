# QR Generator

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Introduction
The **QR Generator** is a simple Node.js application that allows users to generate a QR code from a URL. The application also saves the QR code image and the entered URL into files for easy access. This project is perfect for those looking to quickly generate QR codes for personal or professional use.

## Features
- Prompt users to input a URL.
- Generate a QR code from the provided URL.
- Save the generated QR code as an image file.
- Save the entered URL in a text file.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/qr-generator.git
   cd qr-generator

2. **Install dependencies:**
     ```bash
       npm install
4. **Start the application:**
    ```bash
     npm start
## Usage
1. Run the application using npm start.
2. You will be prompted to enter a URL.
3. The application will generate a QR code image (qr_img.png) from the URL.
4. The entered URL will also be saved in a text file (URL.txt).
## Technologies Used
- **Node.js:** JavaScript runtime for server-side scripting.
- **Inquirer:** For prompting user input in the command line.
- **QR-Image:** For generating QR code images.
- **File System (fs):** For writing the QR code image and URL to files.

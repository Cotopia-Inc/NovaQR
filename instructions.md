# NovaQR — QR Code Generator

NovaQR is a powerful and customizable QR code generator designed for businesses and individuals to create high-quality QR codes effortlessly. This document provides detailed instructions on installation, features, usage, and troubleshooting for the NovaQR application.

![NovaQR Logo](a50a74b3-88f9-4937-ba0c-670d111e371a-1_all_21781.webp)

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage Instructions](#usage-instructions)
  - [Generating a QR Code](#generating-a-qr-code)
  - [Customizing Your QR Code](#customizing-your-qr-code)
- [Advanced Features](#advanced-features)
- [Customization](#customization)
- [Troubleshooting](#troubleshooting)
- [License Information](#license-information)
- [Contact](#contact)

## Introduction
NovaQR is designed to simplify the QR code generation process while offering a variety of customization options. It is suitable for marketing campaigns, event management, and personal sharing.

## Installation

### Prerequisites
- A modern web browser (such as Google Chrome, Mozilla Firefox, Safari, or Microsoft Edge).
- Basic knowledge of HTML, CSS, and JavaScript (optional for customization).

### Installation Steps
1. **Clone the Repository**:
   Open your terminal and run the following command to clone the NovaQR repository:
   ```bash
   git clone https://github.com/Cotopia-Inc/NovaQR
   ```
   Replace `yourusername` with your actual GitHub username.

2. **Navigate to the Project Directory**:
   ```bash
   cd novaqr
   ```

3. **Open in a Browser**: 
   Open `index.html` in your preferred web browser to run the application locally.

4. **Dependencies**: 
   NovaQR uses external libraries for QR code generation and rendering. Ensure you have an internet connection to load these dependencies from CDNs.

## Usage Instructions

### Generating a QR Code
1. **Enter the Content**:
   - In the "URL / Text" input field, type the URL, text, or any information you want to encode into the QR code.

2. **Generate the QR Code**:
   - Click the "Create" button to generate your QR code. The generated QR code will appear on the screen.

3. **Exporting the QR Code**:
   - Use the "Save" button to download your QR code in your selected format (PNG, SVG, or PDF).
   - Choose the desired file format from the dropdown menu before saving.

### Customizing Your QR Code
1. **Redundancy Level**: 
   - Select the desired error correction level from the dropdown menu (L, M, Q, H). Higher redundancy levels allow the QR code to be scanned even when partially damaged.

2. **Module Type**: 
   - Choose the type of modules for your QR code (square, dot, or rounded) to suit your design preferences.

3. **Colors**: 
   - Use the color picker to customize the primary color of the QR code and the background color. You can also enter HEX values for precise color selection.

4. **Logo Integration**:
   - To add a logo, click the "Choose" button next to the logo section and upload an image file. The logo will be centered in the generated QR code.

5. **Real-Time Preview**: 
   - As you make changes, the QR code will update in real-time, allowing you to see how your customizations affect the overall design.

## Advanced Features
- **Dynamic QR Codes**: Create QR codes that can be updated with new links or information without changing the QR code itself.
- **Password Protection**: Set a password for your QR code, ensuring only authorized individuals can access the information.
- **Expiration Dates**: Configure QR codes to expire after a certain date.
- **Analytics and Tracking**: Enable tracking features to gather data on QR code scans, including location and device type.

## Customization
- **Styling**: 
  - To change the look and feel of the application, edit the `styles.css` file. You can modify colors, fonts, and layout to match your brand.

- **JavaScript Functionality**: 
  - The core functionality of NovaQR is contained in `main.js` and `matrix.js`. You can modify these files to add features or adjust existing functionality.

- **Adding Your Logo**: 
  - To change the logo displayed in the application, replace the logo image source in the header section of `index.html` with the URL of your desired logo.

## Troubleshooting
- **QR Code Not Generating**: Ensure that the entered URL or text is valid and does not contain unsupported characters.
- **Logo Not Appearing**: Check the dimensions and format of the logo file. Ensure it is compatible with the QR code.
- **Performance Issues**: If the application runs slowly, consider optimizing images or testing on a more powerful device.
- **Export Errors**: Make sure your browser allows downloads and check for any ad blockers that may interfere.

## License Information
NovaQR is licensed under the **GNU General Public License v3.0**. This license allows users to freely use, modify, and distribute the software, provided that all copies maintain the original license.

For more information, visit [GNU's official website](https://www.gnu.org/licenses/gpl-3.0.html).

## Contact
For support or inquiries, please reach out to:
- **Email**: support@cotopia.org
- **Website**: [www.cotopia.shop](http://www.cotopia.shop)

---

Thank you for using NovaQR! We hope this guide helps you make the most of our QR code generator. If you have any further questions or need assistance, please feel free to contact us.
```


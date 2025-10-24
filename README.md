# NovaQR — QR Code Generator

NovaQR is a powerful and customizable QR code generator designed for businesses, developers, and distributors looking to create unique, high-quality QR codes effortlessly. With features such as logo integration, color customization, and real-time previews, NovaQR is the perfect tool for marketing, event management, and personal use.

![NovaQR Logo](a50a74b3-88f9-4937-ba0c-670d111e371a-1_all_21781.webp)

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Licensing](#licensing)
- [Support and Training](#support-and-training)
- [Marketing Materials](#marketing-materials)
- [FAQs](#faqs)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [Contact](#contact)
- [Changelog](#changelog)

## Features
- **User-Friendly Interface**: Intuitive controls for generating QR codes.
- **Real-time Preview**: See changes instantly as you customize your QR code.
- **Logo Integration**: Add custom logos directly into your QR codes for branding.
- **Color Customization**: Choose primary and background colors to match your branding.
- **Multiple Output Formats**: Export QR codes in PNG and SVG formats.
- **Error Correction Levels**: Select different levels of error correction (L, M, Q, H).
- **Mobile and Desktop Friendly**: Fully responsive design for a seamless experience on any device.
- **Scanning Capability**: Built-in functionality to scan QR codes using device cameras or by uploading images.

## Installation
### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, etc.)
- Basic understanding of HTML, CSS, and JavaScript

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/novaqr.git
   cd novaqr
   ```

2. **Open in a Browser**: 
   Open `index.html` in your preferred web browser to run the application locally.

3. **Dependencies**: 
   NovaQR uses external libraries for QR code generation and rendering. Ensure you have an internet connection to load these dependencies from CDNs.

## Usage
1. **Enter the Content**: In the "URL / Text" field, input the text or URL you want to encode into a QR code.
2. **Customize Your QR Code**:
   - Adjust the **Redundancy Level**: Choose the error correction level (L, M, Q, H).
   - Select the **Module Type**: Choose between square, dot, or rounded modules.
   - Pick the **Primary and Background Colors**: Use the color picker or enter HEX values.
   - Upload a **Logo**: Click "Choose" to upload a logo that will be centered in the QR code.
3. **Generate the QR Code**: Click the "Create" button to generate your QR code.
4. **Export Options**: Use the "Save" button to download your QR code in the selected format (PNG or SVG).
5. **Scanning**: Use the camera or upload an image to scan and decode QR codes.

## Customization
### CSS Styling
- Customize the look and feel of the application by editing the `styles.css` file. You can modify colors, fonts, and layout to fit your branding needs.

### JavaScript Functionality
- The core functionality is contained in `main.js` and `matrix.js`. Feel free to modify these scripts to add features or improve performance.

### Adding Your Logo
- To change the logo displayed in the application, replace the logo image source in the header section of your HTML file with your desired logo URL.

## Licensing
This project is licensed under the **GNU General Public License v3.0**. This means you can use, modify, and distribute this software freely, provided that all copies include the original license and any substantial modifications are made available under the same license.

### Key Points of the GNU v3.0 License:
- **Freedom to Use**: You can use the software for any purpose.
- **Freedom to Study and Modify**: You can study how the program works, and change it to make it do what you wish.
- **Freedom to Distribute**: You can redistribute copies of the original program so you can help others.
- **Freedom to Distribute Modified Versions**: You can distribute copies of your modified versions to others.

For more details on the GNU General Public License v3.0, please visit [GNU's official website](https://www.gnu.org/licenses/gpl-3.0.html).

## Support and Training
- **Included Tech Support**: Distributors receive support for basic troubleshooting, usage guidance, and access to training materials.
- **Onboarding Training**: Distributors will receive training on how to use and promote the NovaQR app effectively.

## Marketing Materials
Distributors will be provided with a marketing kit that includes:
- Product brochures and flyers
- Digital assets for online promotion
- Sample QR codes for demonstrations

## FAQs (Frequently Asked Questions)

### 1. What is a QR code?
A QR code (Quick Response code) is a type of matrix barcode that can be read by smartphones and other devices with a camera. It can store various types of information, including URLs, text, contact information, and more.

### 2. Can I use NovaQR for commercial purposes?
Yes, you can use NovaQR for commercial purposes under the terms of the GNU General Public License v3.0. Make sure to adhere to the licensing requirements.

### 3. What browsers are supported?
NovaQR is designed to work with modern web browsers, including:
- Google Chrome
- Mozilla Firefox
- Safari
- Microsoft Edge

### 4. How do I report a bug?
If you encounter any issues or bugs, please open an issue in the GitHub repository. Include a clear description of the problem, steps to reproduce it, and any relevant screenshots.

## Troubleshooting
- **QR Code Not Generating**: Ensure that the URL or text is valid and does not contain unsupported characters.
- **Logo Not Appearing**: Check the dimensions of the logo file. Ensure it is not too large to cover the finder patterns.
- **Performance Issues**: If the application runs slowly, consider optimizing the images used or testing on a more powerful device.

## Contributing
We welcome contributions to improve NovaQR! If you have suggestions or enhancements, please feel free to submit a pull request or open an issue in the repository. Contributions can include:
- Bug fixes
- New features
- Documentation improvements

### Guidelines
- Please ensure that your code adheres to the existing style and conventions used in the project.
- Include tests where applicable and ensure that existing tests pass.
- Write a clear description of your changes in your pull request.

## Contact
For support or inquiries, please reach out to:
- **Email**: support@cotopia.org
- **Website**: [www.cotopia.shop](http://www.cotopia.shop)

## Changelog
- **v1.0.0** - Initial release with basic QR code generation features.
- **v1.1.0** - Added logo integration and real-time preview functionality.
- **v1.2.0** - Improved mobile responsiveness and user interface enhancements.

---

Thank you for considering NovaQR for your QR code generation needs! We hope you enjoy using the application and find it beneficial for your personal or business requirements.
```
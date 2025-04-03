# QR Code Generator

A simple and user-friendly QR code generator with a graphical interface built using Python.

## Features

- Generate QR codes from text or URLs
- Customizable QR code size
- Multiple error correction levels (L: 7%, M: 15%, Q: 25%, H: 30%)
- Support for PNG and SVG output formats
- Live preview of generated QR codes
- Simple and intuitive graphical interface

## Installation

### Method 1: Using the Setup Script (Recommended)

1. Download and extract the project zip file
2. Open a terminal/command prompt in the project directory
3. Run the setup script:
   ```bash
   python setup.py install
   ```

### Method 2: Manual Installation

1. Ensure you have Python 3.6 or higher installed
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```bash
   python qr.py
   ```

2. Using the GUI:
   - Enter the text or URL you want to encode
   - Select the desired QR code size (in pixels)
   - Choose an error correction level:
     * L (7% error correction)
     * M (15% error correction)
     * Q (25% error correction)
     * H (30% error correction)
   - Select output format (PNG or SVG)
   - Click "Generate QR Code" to preview
   - Click "Save QR Code" to save the file



cat > README.md << 'EOF'
# QR Code Generator

A simple Node.js application that generates QR codes from user-provided URLs and saves the URL to a text file.

## Features

- Takes user input for any URL
- Generates a QR code image (qr_img.png)
- Saves the original URL to a text file (URL.txt)

## Installation

  1. Clone this repository:
     ```bash
     git clone https://github.com/your-username/YoussefChouabi.git
  2. Navigate to the project directory:
     ```bash
     cd QR-Code-Generator
  3.Install the dependencies:
    ```bash
    
      npm install
## Usage
  Run the application with:

     ```bash
        node index.js
  When prompted, enter the URL you want to convert to a QR code. The application will:

  Generate a QR code image as qr_img.png

  Save the original URL in URL.txt

## Dependencies

  inquirer - For user input

  qr-image - For QR code generation

  fs - For file system operations


## License
  This project is open source and available under the ISC License.

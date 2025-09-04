QR Code Generator

A simple Node.js command-line application that generates QR codes from user-provided URLs. The project uses inquirer for interactive prompts and qr-image to generate the QR code image.

🚀 Features

Prompt the user for a URL using an interactive CLI.
Save the entered URL into a text file (URL.txt).
Generate a QR code (qr_img.png) from the provided URL.
Lightweight and easy to use.

📦 Installation

Clone the repository and install dependencies:
git clone https://github.com/your-username/qr-code-generator.git
cd qr-code-generator
npm install

🛠 Usage

Run the app with:
node index.js
Enter a URL when prompted.
The program will:
Save the URL to URL.txt.
Generate a QR code image (qr_img.png) in the project folder.

📂 Project Structure

.
├── index.js        # Main application file
├── package.json    # Project metadata and dependencies
├── package-lock.json
├── URL.txt         # Stores the last entered URL
├── qr_img.png      # Generated QR code image

📚 Dependencies

inquirer – for user input prompts.
qr-image – to generate QR codes.
fs (Node.js built-in) – for file system operations

.

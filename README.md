# PDF to Word Converter

This project is a simple web-based PDF to Word converter. Users can upload a PDF file, and the application will convert it to a Word document using a third-party API.

## Features

- Upload a PDF file
- Convert the PDF file to a Word document
- Download the converted Word document

## Technologies Used

- HTML
- CSS
- JavaScript
- PDF.co API

## How to Use

1. Clone the repository or download the files.
2. Open `index.html` in a web browser.
3. Upload a PDF file using the file input.
4. Click the "Convert" button.
5. Download the converted Word document.

## API Key

This project uses the PDF.co API for converting PDF files to Word documents. To use this project, you need to sign up for an API key from [PDF.co](https://pdf.co/).

Replace `YOUR_API_KEY` in the `script.js` file with your actual API key:

```javascript
headers: {
    'x-api-key': 'YOUR_API_KEY'
}

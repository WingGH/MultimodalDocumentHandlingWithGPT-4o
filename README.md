# MultimodalDocumentHandlingWithGPT-4o
The PDF Analysis Tool is designed to convert PDF documents into images and analyze their content using AI. This tool processes each page of a PDF, encodes the pages as images, and sends them to an AI model to extract specific information based on user-defined questions. Ideal for demonstrations and showcasing AI capabilities, this tool is not for direct production use.

## Features

- Convert PDF pages to images.
- Encode images to Base64 for transmission.
- Send images and questions to an AI model for analysis.
- Parse and store the responses in JSON format.

## Requirements

- Python 3.9+

## Installation

Install the dependencies with the following command:

```bash
pip install PyMuPDF Pillow requests

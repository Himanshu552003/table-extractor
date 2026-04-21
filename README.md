# Table Extractor Flask App

A web application built with Flask that allows users to upload PDF files and extract tables from them. The extracted tables are displayed as HTML tables and can be exported to Excel format.

## Features

- Upload PDF files through a web interface
- Extract tables from PDF pages using pdfplumber
- Display extracted tables in HTML format
- Export tables to Excel (.xlsx) file
- Simple and intuitive web interface

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Himanshu552003/table-extractor.git
   cd table-extractor
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   Or install manually:
   ```bash
   pip install flask pdfplumber pandas openpyxl
   ```

## Usage

1. Run the Flask application:
   ```bash
   python app.py
   ```

2. Open your web browser and go to `http://127.0.0.1:5000`

3. Upload a PDF file using the web interface

4. View the extracted tables and download the Excel file

## Dependencies

- Flask: Web framework
- pdfplumber: PDF table extraction
- pandas: Data manipulation and Excel export
- openpyxl: Excel file handling
- werkzeug: File handling utilities (included with Flask)

## Project Structure

```
Table-Extractor-Flask-App/
├── app.py                 # Main Flask application
├── templates/
│   └── home.html         # HTML template for the web interface
├── static/
│   └── uploads/          # Directory for uploaded PDF files
├── images/               # Static images
├── extracted_tables.xlsx # Generated Excel file (not in repo)
└── README.md            # This file
```

## Contributing

Feel free to submit issues and pull requests.

## License

This project is open source. Please check the license file for details.
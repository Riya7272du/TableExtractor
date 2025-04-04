# PDFTableExtractor
This Python project helps you extract tables from PDF files (like bank statements or reports) and save them as Excel files (.xlsx).

# What Does It Do?
1. Reads PDF files from the input folder
2. Looks for tables inside the PDF (based on spaces and alignment)
3. Converts those tables into Excel sheets
4. Saves the Excel files into the extracted folder

# Tools Used
1. Python
2. PyPDF2 – to read text from PDF files
3. Pandas – to work with tables and save them as Excel
4. openpyxl – to format Excel files

# Folder Structure
project-folder/
│
├── input/              # Put your PDF files here
├── extracted/          # Excel files will be saved here
├── pdf_table_extraction.py  # Main Python script

# How to Run It
    Make sure Python is installed on your computer.

    Install the required libraries by running:
        -pip install pandas openpyxl PyPDF2
    
    Place your PDF files into the input/ folder.

    Run the script:
        -python pdf_table_extraction.py

    Check the extracted/ folder for your Excel files.


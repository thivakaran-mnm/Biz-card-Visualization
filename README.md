# BizcardX: Business Card Data Extraction with OCR

Bizcard is a Python application designed to extract information from business cards using Optical Character Recognition (OCR). It allows users to upload images of business cards, extract relevant details such as name, designation, contact information, etc., and store them in a MySQL database.

## Table of Contents

- Technologies Used
- Features
- Installation
- Usage

## Technologies Used

1. Python
2. Streamlit
3. EasyOCR
4. MySQL
5. Pandas

## Features

- **Image Upload:** Users can upload images of business cards in formats like PNG, JPG, or JPEG.
- **Text Extraction**: The application uses EasyOCR to extract text from uploaded images.
- **Data Processing:** Extracted text is processed to identify key details such as name, designation, contact information, etc.
- **Database Integration:** Extracted information is stored in a MySQL database for future reference.
- **Preview and Modification:** Users can preview extracted information and modify details if necessary before saving.
- **Delete Entries:** Users can delete entries from the database based on selected criteria.

## Installation

- Clone the repository
- Install dependencies: pip install -r requirements.txt
- Set up a MySQL database and configure the connection details in the code.
- Run the Streamlit application: streamlit run bisz.py

## Usage

- Access the application in your web browser.
- Follow the instructions to upload business card images, extract data, and perform various operations.

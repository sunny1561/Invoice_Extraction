# Invoice Extraction App using Streamlit :
An automated app that extracts structured data from invoice images.
Users can upload invoice images as ZIP files or individual images (PNG, JPG, JPEG).
# Note: The app extracts the following key details from the invoices( You can Change these attributes based on your use cases)
# Invoice Number 
# Date 
# Vendor Name  
# Items (name, quantity, price) 
# Total Amount 
Uses advanced AI models (Ollama Llama3.2) for accurate image-based data extraction.
Extracted data is displayed in a structured table format.
Allows users to download the extracted data as a CSV file.

# How it can be useful in real life:
# 1. Automated Invoice Processing:

# 2. Businesses can automatically extract data from invoice images, saving time on manual data entry.
Expense Tracking:

# 3. Streamline expense tracking for businesses or freelancers by extracting invoice details for easier record keeping.
Data Entry Automation:

# 4. Reduces the need for manual data entry, ensuring faster and more accurate invoice processing. Integration with Accounting Systems:

# 5. Exported CSV files can be integrated into accounting or ERP systems for efficient financial management. 

# 6. Invoice Management for Small Businesses:
Small businesses can process and maintain organized records of their invoices with ease.
# Features:
Multiple Upload Options:

Upload a ZIP file containing multiple invoice images or individual invoice image files.
Easy Extraction:

Extracts all necessary information from invoices and organizes it into a structured format.
Downloadable CSV:

Allows you to download the structured invoice data in a CSV format for easy processing and record keeping.



## Running the App Locally:
Clone or download this repository to your local machine.
Navigate to the directory containing the app.
Run the following command to start the Streamlit app:

## streamlit run invoice_extraction_app.py

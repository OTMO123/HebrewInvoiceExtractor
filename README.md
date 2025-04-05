# Enhanced Invoice Processor for Hebrew Documents
This code is a comprehensive Python solution designed to automatically process and extract product information from invoices and receipts written in Hebrew, particularly for food products. The system uses Anthropic's Claude API for image recognition and text extraction.
Key Features:

PDF Processing: Splits large PDFs into manageable chunks and converts them to high-quality images.
Intelligent Document Classification: Pre-screens documents to identify only those containing food-related information, saving processing time and API costs.
Hebrew Text Extraction: Specialized in recognizing and extracting Hebrew text from images, with translation to English.
Structured Data Extraction: Extracts product names, prices, quantities, and units from invoices.
Fuzzy Matching: Implements fuzzy matching to compare extracted products with existing product lists in Excel.
Excel Integration: Updates existing Excel files with extracted information and creates detailed reports.
Error Handling and Retry Logic: Robust error handling with multiple retry attempts for API failures.

Use Case:
This tool is particularly useful for businesses that deal with Hebrew invoices for food products and need to automate the extraction of product information for inventory management, accounting, or data analysis purposes.
Technologies Used:

Python for core functionality
Anthropic Claude API for advanced image recognition and text extraction
PDF2Image for PDF processing
Pandas for data manipulation
FuzzyWuzzy for text matching
Google Colab integration for easy file handling

Setup and Usage:
The code is designed to run in Google Colab, where users can:

Enter their Anthropic API key
Upload PDF invoices and Excel product lists
Process the documents
Download the updated Excel files with extracted information

The system includes detailed logging and statistics to track processing performance and results.

Invoice Generator using JSON  

Overview  

This project provides a Python-based Invoice Generator that automates the creation of professional invoices. It reads data from a JSON file, processes the information (e.g., company details, client details, itemized lists), calculates totals, and generates a formatted PDF invoice.  

Features  

- Accepts input from a structured JSON file for easy configuration.  
- Automatically calculates totals, including tax and discounts.  
- Generates a PDF invoice with a clean and professional layout.  
- Customizable for different business needs (e.g., logos, payment terms).  

Flowchart  

<img width="500" alt="image" src = "https://github.com/Madan1710/invoice_generator/blob/main/flowchart.png">

Methodology  

1. **Input Handling**: Load and validate invoice data from a structured JSON file to ensure consistency.  
2. **Data Parsing**: Extract fields such as company info, client info, itemized details, tax, and discount rates for processing.  
3. **Invoice Generation**: Create a formatted invoice layout using the `reportlab` library for PDF output.  
4. **Output Management**: Save the generated invoice as a PDF file, ready for sharing or printing.  


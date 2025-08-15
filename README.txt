 Product Information Scanner

An OCR-based system that extracts text from product labels and retrieves nutritional information from Open Food Facts database.

📋 Approach

1. Image Processing:
   - Users upload product label images
   - System processes images with EasyOCR for text extraction

2. Text Analysis:
   - Extracts all readable text from the image
   - Identifies potential product names and key features

3. Database Lookup:
   - Queries Open Food Facts API with extracted text
   - Returns the best matching product information

4. Results Display:
   - Shows extracted text with bounding boxes
   - Displays formatted product information
   - Includes nutritional data when available

 Setup Instructions

Prerequisites
- Python 3.6+
- Google Account (for Colab) or Jupyter Notebook for local execution

Google Colab (Recommended)
1. Open the notebook in Colab:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-repo/your-notebook.ipynb)
2. Run all cells (Runtime > Run all)
3. Upload your product image when prompted

Local Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/product-scanner.git
   cd product-scanner

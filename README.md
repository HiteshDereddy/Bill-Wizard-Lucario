# BillWizard

BillWizard is a desktop application that captures video input from a webcam or pre-recorded video to detect total bill amounts from invoices using Optical Character Recognition (OCR). The application also categorizes invoices based on their content using machine learning algorithms.

## Features

- **Video Input:** Capture invoices in real-time or from pre-recorded videos.
- **OCR for Bill Amount Detection:** Utilizes Tesseract OCR to extract and recognize the total amount from invoices.
- **Invoice Categorization:** Classifies invoices into predefined categories (e.g., groceries, electronics, services) using machine learning.
- **Data Export:** Allows users to export detected amounts and categories in structured formats (CSV, JSON, XML).

## Tech Stack

- **Programming Language:** Python
- **Libraries:**
  - OpenCV for video input
  - Tesseract for OCR
  - Scikit-learn or TensorFlow for invoice categorization

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your_username/BillWizard.git
   cd BillWizard

## README

### Overview
This program performs OCR (Optical Character Recognition) on all PDF files in the `input` folder and saves the processed, searchable PDFs to the `output` folder. It uses [ocrmypdf](https://ocrmypdf.readthedocs.io/) and supports multiple languages, currently set to Portuguese and English (`por+eng`).

### Features
- Batch processing of PDFs
- Automatic deskew and page rotation
- Multi-language OCR support (customizable via the `LANGUAGES` variable)
- Output files are saved with `_iter` appended to the original filename

### Usage
1. Install dependencies as described above.
2. Place your PDF files in the `input` directory.
3. Run all cells in the notebook.
4. Find the OCR-processed PDFs in the `output` directory.

### Customization
- To change the OCR languages, modify the `LANGUAGES` variable (e.g., `'por+eng+spa'` for Portuguese, English, and Spanish).
- Adjust input/output folder paths as needed.

### Credits
Created by Felipe Bertoglio @ INF-UFRGS 2025.

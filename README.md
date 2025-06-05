"File to read the form and extract texts"
# Optical Character Recognition for W2 Form

This project implements an end-to-end pipeline for **automated extraction of key fields from IRS W-2 tax forms** using Optical Character Recognition (OCR). It utilizes computer vision and text processing techniques to detect and extract structured data from scanned images of W-2 forms.

## Project Overview

Manually entering data from W-2 forms is time-consuming and error-prone. This project streamlines that process by:
- Preprocessing scanned W-2 forms for OCR
- Detecting and extracting specific fields (e.g., Employer EIN, Wages, Federal Income Tax Withheld, etc.)
- Structuring the extracted data into a JSON-like dictionary format

### Sample Use Case:
Automated pre-filling of tax forms or backend data ingestion for accounting software.

---

## Tech Stack

- **Python**
- **OpenCV** - Image preprocessing and contour detection
- **Tesseract OCR** - Text extraction from image regions
- **Pytesseract** - Python wrapper for Tesseract
- **NumPy, Matplotlib** - Image handling and visualization

---

## Features

-  Automatic W-2 form alignment and rotation correction
- Field localization using image segmentation
- OCR-based extraction of key W-2 fields:
  - Employer Identification Number (EIN)
  - Wages, Tips, and Other Compensation
  - Federal Income Tax Withheld
  - Social Security and Medicare Wages
-  Structured dictionary output for integration with downstream tools



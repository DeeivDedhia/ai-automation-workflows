# Automated Image Processing & Google Drive Upload Workflow

An automated image processing workflow built using n8n, Google Sheets, JavaScript, and Google Drive. This workflow fetches image URLs from Google Sheets, analyzes image dimensions, resizes images automatically, and uploads them into categorized Google Drive folders based on image size and format.

---

## Features

- Automated image downloading from URLs
- Image dimension detection
- Smart image categorization
- Automatic image resizing
- JPEG & PNG conversion
- Google Drive integration
- Batch image processing
- Conditional workflow logic
- Dynamic file naming

---

## Workflow Overview

1. Read image URLs from Google Sheets
2. Download images automatically
3. Detect image dimensions and format
4. Categorize images based on size
5. Resize large images to optimized dimensions
6. Convert images into JPEG/PNG formats
7. Upload processed images into Google Drive folders

---

## Technologies Used

- n8n
- JavaScript
- Google Sheets API
- Google Drive API
- HTTP Requests
- Image Processing Automation

---

## Core Functionalities

### Image Analysis
- Detects width and height
- Identifies image format
- Checks image size thresholds

### Image Optimization
- Resizes images to 1200x1200
- Converts images into optimized formats
- Cleans and standardizes file names

### Automated File Management
- Uploads small images separately
- Organizes images into dedicated folders
- Supports batch automation workflows

---

## Workflow Logic

### Small Images
Images smaller than defined dimensions are:
- detected automatically
- separated into dedicated folders

### Large Images
Large images are:
- resized automatically
- converted into optimized JPEG/PNG formats
- uploaded into categorized Google Drive folders

---

## Project Structure

Image-Processing-Automation/
│
├── workflow.json
├── README.md
└── screenshots/
Example Use Cases
Bulk image optimization
Ecommerce image processing
Automated media management
AI dataset preparation
Social media asset optimization
Image archival workflows
Security Notice

All API keys, credentials, Google Drive IDs, spreadsheet IDs, and sensitive information have been removed before publishing this repository publicly.

Author
Deeiv Dedhia

License
This project is intended for educational and portfolio purposes only.

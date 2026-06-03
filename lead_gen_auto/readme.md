# Apollo Lead Generation Automation

An automated lead generation and contact enrichment workflow built using n8n, Apollo.io, Apify, and Google Sheets. This workflow dynamically generates Apollo search URLs, scrapes business leads, enriches contact information, removes duplicates, and stores clean lead data directly into Google Sheets.

---

## Features

- Automated Apollo.io lead scraping
- Dynamic search URL generation
- Multi-location business targeting
- Contact enrichment (emails, phone numbers, LinkedIn URLs)
- Duplicate lead removal
- Google Sheets integration
- Reusable workflow automation
- Supports industry & job-title based targeting

---

## Workflow Overview

1. Receive search parameters
2. Generate dynamic Apollo.io search URL
3. Scrape leads using Apify Apollo Scraper
4. Extract and transform lead information
5. Remove duplicate leads
6. Store clean lead data in Google Sheets

---

## Technologies Used

- n8n
- Apollo.io
- Apify API
- Google Sheets API
- JavaScript

---

## Data Extracted

- Full Name
- Email Address
- Phone Number
- Company Name
- Job Title
- LinkedIn URL
- Website URL
- Location
- Industry
- Seniority

---

## Example Use Cases

- B2B Lead Generation
- Sales Prospecting
- Founder & CEO Outreach
- Market Research
- Recruitment Lead Collection
- Business Database Building

---

## Project Structure
Lead-Scraping/
│
├── workflow.json
├── README.md
└── screenshots/
Security Notice
All API keys, spreadsheet IDs, and sensitive credentials have been removed before publishing this repository publicly.

Author
Deeiv Dedhia

License:
This project is intended for educational and portfolio purposes only.

# AI Gmail Management Agent

## Overview

AI Gmail Management Agent is an intelligent email automation workflow built using n8n, OpenAI, Gmail API, and Google Sheets. The system automatically monitors incoming emails, classifies them into predefined categories, generates summaries, drafts personalized responses, and manages inbox organization without manual intervention.

The workflow helps reduce inbox clutter, improve response efficiency, and automate repetitive email management tasks.

---

## Features

### Email Classification

Automatically categorizes incoming emails into:

* Promotions
* Social Media
* Personal Emails
* Sales Inquiries
* Other Emails

### Smart Labeling

Applies Gmail labels automatically based on the detected email category.

### AI Email Summarization

Generates concise summaries of incoming emails using OpenAI to help users quickly understand email content.

### Automated Draft Generation

Creates professional draft replies for personal emails using AI-generated responses.

### Sales Email Auto-Replies

Generates and sends intelligent responses to sales-related emails automatically.

### Google Sheets Logging

Stores email metadata and AI-generated summaries in Google Sheets for tracking and future reference.

### Inbox Management

Automatically marks promotional emails as read and manages email status based on category.

---

## Workflow Architecture

1. Gmail Trigger monitors incoming emails.
2. AI Text Classifier categorizes emails into predefined categories.
3. Category-specific actions are executed:

   * Promotions → Apply label and mark as read.
   * Social Emails → Generate summary and save to Google Sheets.
   * Personal Emails → Generate draft response.
   * Sales Emails → Generate and send AI-powered reply.
   * Other Emails → Mark as unread for manual review.
4. Results are stored and managed automatically.

---

## Tech Stack

* n8n
* OpenAI GPT-4.1 Mini
* Gmail API
* Google Sheets API
* Workflow Automation
* AI-Powered Text Classification
* Email Processing Automation

---

## Business Impact

* Reduces manual email management effort.
* Improves inbox organization and prioritization.
* Speeds up email response workflows.
* Automatically documents important email summaries.
* Enhances productivity through AI-powered automation.

---

## Future Improvements

* Sentiment analysis for incoming emails.
* Priority scoring and urgency detection.
* Calendar event extraction from emails.
* CRM integration for lead management.
* Slack and Microsoft Teams notifications.
* Multi-language email support.

---

## Author

Deeiv Dedhia

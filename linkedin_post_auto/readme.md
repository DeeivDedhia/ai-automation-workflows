# AI LinkedIn Content Automation

An AI-powered content automation workflow built using n8n that generates professional LinkedIn posts, creates AI-generated marketing visuals, sends content to Telegram, uploads assets to Google Drive, and logs activity into Google Sheets.

---

## Overview

This workflow automates the complete process of creating LinkedIn-ready content using AI agents and external APIs.

The system:

* Researches a topic using Tavily Search
* Generates a professional LinkedIn post using GPT-4.1
* Creates an AI image prompt from the generated content
* Generates a marketing-style image using OpenAI Image Generation
* Sends the post and image to Telegram
* Uploads generated assets to Google Drive
* Logs workflow outputs into Google Sheets

---

## Features

* AI-generated LinkedIn posts
* Real-time web research using Tavily API
* AI-generated image prompts
* AI marketing image generation
* Telegram content delivery
* Google Drive integration
* Google Sheets logging
* Structured AI output parsing
* Multi-agent workflow architecture

---

## Workflow Architecture

```text
Trigger
   ↓
Tavily Research
   ↓
GPT-4.1 LinkedIn Post Generation
   ↓
Image Prompt Agent
   ↓
OpenAI Image Generation
   ↓
Convert to Binary
   ↓
Telegram Delivery
   ↓
Google Drive Upload
   ↓
Google Sheets Logging
```

---

## Tech Stack

* n8n
* OpenRouter GPT-4.1
* OpenAI Image API
* Tavily Search API
* Telegram Bot API
* Google Drive API
* Google Sheets API

---

## Inputs

The workflow accepts:

```json
{
  "postTopic": "AI Automation",
  "targetAudience": "Business Owners",
  "chatID": "YOUR_TELEGRAM_CHAT_ID"
}
```

---

## Setup

1. Import the workflow JSON into n8n
2. Configure credentials for:

   * OpenRouter
   * OpenAI
   * Tavily
   * Telegram
   * Google Drive
   * Google Sheets
3. Update folder IDs and sheet IDs
4. Execute the workflow

---

## Use Cases

* LinkedIn personal branding
* AI-powered content marketing
* Marketing automation
* Social media content pipelines
* Creator workflows
* Agency automation systems

---

## Notes

This project is intended for educational and portfolio purposes.
Some APIs and integrations require valid credentials and environment configuration before execution.

---

## Author

Deeiv Dedhia

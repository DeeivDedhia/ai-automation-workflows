# AI Social Media Automation Workflow

An AI-powered multi-platform social media automation workflow built using n8n.

This workflow generates AI-based social media content, creates image prompts, generates visuals using Leonardo AI, and distributes content across multiple platforms including Instagram, Facebook, LinkedIn, and YouTube.

---

## Overview

The workflow automates the process of:

* Reading content topics from Google Sheets
* Generating captions using Google Gemini
* Creating AI image prompts
* Generating images using Leonardo AI
* Posting content across multiple social media platforms
* Updating posting status automatically
* Logging generated content into Google Sheets

---

## Features

* AI-generated social media captions
* Multi-platform publishing workflow
* Instagram posting automation
* Facebook posting automation
* LinkedIn posting workflow
* YouTube upload automation
* Leonardo AI image generation
* Google Sheets integration
* Automated status tracking
* Conditional platform routing

---

## Workflow Architecture

```text id="oh1d2n"
Google Sheets
      ↓
Google Gemini AI
      ↓
Caption & Prompt Generation
      ↓
Leonardo AI Image Generation
      ↓
Platform Routing
 ┌────────┬────────┬────────┬────────┐
 ↓        ↓        ↓        ↓
Instagram Facebook LinkedIn YouTube
      ↓
Status Tracking & Logging
```

---

## Technologies Used

* n8n
* Google Gemini AI
* Leonardo AI API
* Facebook Graph API
* LinkedIn API
* YouTube API
* Google Sheets API

---

## Use Cases

* AI content marketing
* Social media automation
* Creator workflows
* Marketing agency automation
* AI-assisted content pipelines
* Multi-platform content publishing

---

## Notes

This workflow is a prototype/demo automation project intended for educational and portfolio purposes.

Some integrations may require:

* valid API credentials
* updated platform permissions
* environment variable configuration
* media formatting adjustments

before full production deployment.

---

## Author

Deeiv Dedhia

# AI Shopify Assistant

An AI-powered Shopify management assistant built using n8n, Telegram, OpenAI, and Shopify APIs.

This workflow allows users to manage Shopify store operations directly through natural language conversations on Telegram.

---

## Overview

The workflow acts as an AI ecommerce assistant capable of interacting with a Shopify store using conversational commands.

Users can:

* Check products
* Create new products
* Update products
* Retrieve orders
* Update orders
* Perform calculations
* Trigger Gmail notifications
* Use web search tools

All actions are executed through an AI Agent connected to multiple Shopify tools and integrations.

---

## Features

* AI-powered Shopify assistant
* Telegram chatbot interface
* Natural language product management
* Product creation automation
* Product update automation
* Order retrieval and updates
* AI memory integration
* Gmail notification support
* Web search integration using SerpAPI
* Multi-tool AI agent architecture

---

## Workflow Architecture

```text id="jlwm9t"
Telegram User
      ↓
Telegram Trigger
      ↓
AI Agent
 ┌──────────────┬──────────────┬──────────────┬──────────────┐
 ↓              ↓              ↓              ↓
Products     Orders        Gmail         Web Search
 ↓              ↓              ↓              ↓
Shopify APIs  Shopify APIs  Gmail API     SerpAPI
      ↓
Telegram Response
```

---

## Technologies Used

* n8n
* OpenAI
* Shopify API
* Telegram Bot API
* Gmail API
* SerpAPI
* AI Agent Architecture

---

## Capabilities

### Product Management

Example:

```text id="jlwm47"
Add a product named carve with description description to be snowboard
```

The AI assistant automatically creates the product inside Shopify.

---

### Product Retrieval

Example:

```text id="jjlwm0"
How many products do you have?
```

The workflow retrieves Shopify store product information and responds directly on Telegram.

---

### Order Management

The workflow supports:

* fetching orders
* updating orders
* managing Shopify operations through AI commands

---

## Workflow Components

### AI Agent

Central orchestration layer handling:

* reasoning
* tool selection
* memory
* conversational flow

---

### Shopify Integrations

Connected Shopify tools include:

* Get Products
* Create Product
* Update Product
* Get Orders
* Update Orders

---

### Telegram Interface

Acts as the conversational frontend for interacting with the AI assistant.

---

### Memory System

Maintains conversational context during interactions.

---

## Setup

1. Import workflow into n8n
2. Configure:

   * OpenAI credentials
   * Shopify API credentials
   * Telegram Bot credentials
   * Gmail credentials
   * SerpAPI credentials
3. Activate workflow
4. Start chatting with the Telegram bot

---

## Use Cases

* AI ecommerce assistant
* Shopify automation
* AI-powered store management
* Conversational ecommerce operations
* Ecommerce workflow automation
* Telegram business assistants

---

## Notes

This project is intended for educational and portfolio purposes.

Some integrations require valid API credentials and Shopify store access for full functionality.

---

## Author

Deeiv Dedhia

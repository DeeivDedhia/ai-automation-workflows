# AI Calendar Scheduling Agent

An AI-powered calendar assistant built using n8n and OpenAI that can create calendar events, schedule meetings with attendees, and retrieve upcoming events using natural language commands.

---

## Overview

This workflow acts as an intelligent scheduling assistant capable of interacting with Google Calendar through AI-powered automation.

The agent can:

* Create calendar events
* Schedule meetings with attendees
* Fetch and summarize upcoming events
* Understand natural language date/time requests
* Automatically determine scheduling intent

---

## Features

* AI-powered calendar assistant
* Natural language scheduling
* Google Calendar integration
* Automatic attendee handling
* Event retrieval and summarization
* Intelligent tool selection
* Error handling workflow
* Multi-tool AI agent architecture

---

## Workflow Architecture

```text
User Request
      ↓
AI Calendar Agent
      ↓
OpenAI Chat Model
      ↓
Tool Selection Logic
 ┌──────────────┬──────────────────────┬──────────────┐
 ↓              ↓                      ↓
Get Events   Create Event   Create Event with Attendee
      ↓
Response Handling
 ┌───────────┬───────────┐
 ↓           ↓
Success   Error Response
```

---

## Technologies Used

* n8n
* OpenAI
* Google Calendar API
* AI Agent Architecture
* LangChain Nodes

---

## Capabilities

### Create Calendar Events

The AI agent can create events using natural language prompts.

Example:

```text
Schedule a meeting tomorrow at 4 PM
```

---

### Schedule Meetings with Attendees

Example:

```text
Schedule a call with john@example.com next Monday at 2 PM
```

---

### Retrieve Upcoming Events

Example:

```text
What meetings do I have tomorrow?
```

---

## How It Works

1. User sends a scheduling request
2. OpenAI analyzes the intent
3. The AI agent selects the correct calendar tool
4. Google Calendar executes the action
5. Workflow returns a success or error response

---

## Setup

1. Import the workflow into n8n
2. Connect:

   * OpenAI credentials
   * Google Calendar credentials
3. Configure your calendar email
4. Execute the workflow

---

## Use Cases

* Personal productivity assistant
* AI scheduling systems
* Smart meeting management
* Voice assistant backend
* Business workflow automation
* AI-powered calendar operations

---

## Notes

This project is intended for educational and portfolio purposes.

Google Calendar credentials and OpenAI API access are required for full functionality.

---

## Author

Deeiv Dedhia

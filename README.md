# AI News Digest Automation

An automated AI news digest workflow built with n8n, Cohere AI, RSS feeds, and Gmail.

## Features

- Fetches latest AI news from RSS feeds
- Summarizes articles using Cohere AI
- Generates HTML-formatted news digests
- Sends daily email reports via Gmail
- Fully automated using n8n Schedule Trigger

## Workflow

Schedule Trigger
→ RSS Read
→ AI Agent (Cohere)
→ Aggregate
→ Gmail

## Tech Stack

- n8n
- Cohere AI
- Gmail API
- RSS Feeds
- HTML Email Templates

## Setup

1. Import the workflow JSON into n8n
2. Configure Cohere API credentials
3. Configure Gmail OAuth
4. Add RSS feed URLs
5. Activate the workflow

## Use Case

This project automates AI news monitoring and delivers concise daily summaries directly to email.

## Author

Ayush Shinde

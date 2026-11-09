# RSS Feed to Telegram Channel (n8n Automation)

This n8n workflow automatically fetches sports news from an RSS feed and publishes it directly to a designated Telegram channel using a Telegram Bot.

## Workflow Overview
1. **RSS Feed Trigger**: Periodically fetches the latest entries from a selected sports news RSS source.
2. **Telegram Node**: Sends the formatted title, description, and link of the news article to the Telegram channel via a bot (`@mcin8nsport`).

## Prerequisites
- **n8n Instance** (Hosted on a VPS / ParsPack)
- **Telegram Bot** created via [@BotFather](https://t.me/BotFather)
- **Telegram Channel** with the bot added as an **Administrator** with *Post Messages* permission.

## Setup Instructions
1. Import the `RSS to Telegram_Sport News.json` file into your n8n dashboard.
2. Create a new Telegram API credential in n8n and insert your Bot Token.
3. Update the `Chat ID` in the Telegram node with your target channel ID (e.g., `-100xxxxxxxxxx`).
4. Activate the workflow and test it via **Execute Workflow**.

---
Developed by Erfaneh | Web Designer & SEO Specialist

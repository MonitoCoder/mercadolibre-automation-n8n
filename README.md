# Mercado Libre Automation with n8n

Real-world automation system built for my own e-commerce business.

## Features

- Receives Mercado Libre webhooks
- Detects new sales and customer questions
- Fetches full order data through REST API
- Sends Telegram alerts
- Product/folder matching workflow
- Conditional routing with n8n
- JSON data transformation

## Stack

- n8n
- Mercado Libre API
- Webhooks
- HTTP Requests
- JavaScript
- Telegram Bot API

## Architecture

Mercado Libre → Webhook → n8n → IF logic → HTTP Request → Process → Telegram

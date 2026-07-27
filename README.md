# AI Contact Form → Google Sheets → Gmail

## Overview

This project is an n8n workflow that automates contact form submissions.

## Workflow Preview

![Workflow](images/workflow.png)

When a user submits the form:

- Receives data through a Webhook
- Stores the submission in Google Sheets
- Sends an email notification using Gmail
- Returns a JSON success response

## Workflow

Webhook
↓
Edit Fields
↓
Google Sheets
↓
Gmail
↓
Respond to Webhook

## Technologies

- n8n
- Google Sheets API
- Gmail API
- Webhooks
- JSON

## Features

- Automatic data collection
- Email notifications
- Cloud spreadsheet storage
- JSON API response

## Author

Yassine El Hayani

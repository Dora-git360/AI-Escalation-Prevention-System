# AI Escalation Prevention System 🚨

An AI-powered customer support automation system built using n8n and Gemini AI to detect high-risk customer tickets and trigger escalation workflows.

## Problem

Customer issues can become escalations when complaints are repeated, urgent, or unresolved.

Support teams need early detection to prevent customer dissatisfaction.

## Solution

This automation analyzes incoming customer tickets using Gemini AI and automatically:

- Classifies ticket priority
- Detects customer sentiment
- Calculates escalation risk score
- Determines SLA urgency
- Logs incidents
- Sends escalation alerts

## Workflow

Customer Ticket
        ↓
Webhook Trigger
        ↓
n8n Automation
        ↓
Gemini AI Analysis
        ↓
JSON Processing
        ↓
Priority Decision
        ↓
Google Sheets Logging
        ↓
Email Escalation Alert

## AI Analysis Example

Input:

Payment deducted but order not placed. Second complaint from customer.

AI Output:

- Priority: P1
- Department: Payments
- Sentiment: Negative
- Risk Score: 90/100
- SLA: 2 Hours

## Technologies Used

- n8n Workflow Automation
- Google Gemini AI
- Webhooks
- REST API Concepts
- JavaScript JSON Processing
- Google Sheets API
- SMTP Email Automation

## Features

✅ AI ticket analysis  
✅ Escalation risk detection  
✅ Automated support workflows  
✅ Real-time email alerts  
✅ Ticket tracking dashboard

## Future Improvements

- Connect Salesforce CRM
- Add Slack/Teams notifications
- Add historical risk prediction
- Build customer health dashboard

# AI Email Agent – n8n + OpenAI + Google Sheets + Gmail

This project is a fully automated AI Email Agent built using n8n.  
It reads tasks from Google Sheets, generates personalized HTML emails using OpenAI,
and sends them automatically through Gmail.

## Features
- Reads structured tasks from Google Sheets
- Inserts recipient name dynamically
- Generates email content using OpenAI with strict formatting rules
- Sends well-formatted HTML emails through Gmail
- No function nodes required
- Fully no-code/low-code setup

## How It Works

1. **Google Sheets → Pending email tasks**  
   Each row contains recipient, subject, message type, name, and content.

2. **OpenAI Node**  
   Generates a clean, HTML-formatted email using a strict prompt.

3. **Gmail Node**  
   Sends the generated HTML email to the desired recipient.

## Files in This Repo
- `email-agent-workflow.json` — the full n8n workflow you can import directly.
- `README.md` — documentation and explanation of the project.

## Requirements
- n8n account
- Google Sheets API credential
- Gmail credential
- OpenAI API key

## Use Cases
- Automated follow-up emails  
- Customer support replies  
- Outreach and reminders  
- Personal or business email tasks  
- Any repetitive message that AI can write for you

## Importing the Workflow
1. Open n8n  
2. Click **Import**  
3. Select `email-agent-workflow.json`  
4. Add your credentials  
5. Run the workflow

## Future Improvements
- Status updates back to Google Sheets
- Batch email sending
- Tone selector (formal, friendly, short, long)
- Attachment support
- Inbox reply automation

---

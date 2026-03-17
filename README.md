# AI-Research-and-Report-generator
🤖 AI Research & Report Generator (n8n Workflow)

An advanced AI-powered research automation system built using n8n that transforms a simple topic input into a fully structured, professional PDF report, delivered directly via email.

🚀 Features

📌 Topic-based AI research generation

🧠 Multi-agent AI pipeline (Research → Strategy → Report → Editing)

📊 Structured insights with trends, stats, opportunities & risks

📝 Professional report formatting

📄 Automatic PDF generation

📧 Email delivery with download link

⚡ Fully automated workflow (no manual effort)

🏗️ Workflow Overview

This workflow uses a multi-stage AI pipeline:

1. Form Input

Collects:

Topic

Email

Triggered via n8n Form node

2. AI Research Agent

Generates:

Key facts

Trends

Statistics

Opportunities

Risks

Future outlook

3. Strategic Analysis Agent

Produces:

Strategic insights

Implications

Risks

Future direction

4. Report Writer Agent

Converts research into:

Executive Summary

Topic Overview

Key Insights

Risks & Challenges

Opportunities

Conclusion

5. Editor Agent

Refines report:

Improves clarity

Fixes grammar

Makes it executive-ready

6. HTML Generator (Code Node)

Converts Markdown → HTML

Applies clean professional styling

7. PDF Generator

Converts HTML → PDF using HTML-to-PDF API

8. Email Delivery

Sends user:

📎 PDF download link

📩 Direct email notification

🔄 Workflow Architecture
Form Trigger
   ↓
AI Research Agent
   ↓
Strategic Analysis Agent
   ↓
Report Writer Agent
   ↓
Editor Agent
   ↓
Code (Markdown → HTML)
   ↓
HTML → PDF
   ↓
Send Email
🧰 Tech Stack

n8n – Workflow automation

Google Gemini API – AI processing

HTML/CSS – Report formatting

HTML to PDF API – PDF generation

SMTP – Email delivery

⚙️ Setup Instructions
1. Import Workflow

Copy JSON

Import into n8n

2. Configure Credentials
🔑 Google Gemini API

Add credentials in:

Google Gemini Chat Model

Use your API key

📄 HTML to PDF API

Add API credentials to:

Convert HTML to PDF

📧 SMTP Email

Configure:

SMTP host

Port

Email & password

3. Activate Workflow

Enable the workflow in n8n

Access form URL

📥 Usage

Open the form

Enter:

Topic (e.g., "Artificial Intelligence in Healthcare")

Email

Submit

Receive:

📄 AI-generated PDF report 

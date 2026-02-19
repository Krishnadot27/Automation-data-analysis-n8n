# Automation of Data Analysis using n8n

An automated n8n workflow that accepts CSV uploads via a form,
analyzes data using Google Gemini AI, generates charts via QuickChart,
and emails the full report to the user.

## 🔧 Tech Stack
- n8n (workflow automation)
- Google Gemini (AI analysis)
- QuickChart.io (chart generation)
- Gmail (email delivery)

## 🚀 How It Works
1. User submits CSV + email via n8n form
2. Workflow extracts and aggregates the data
3. Gemini LLM generates analysis and chart config
4. Charts rendered via QuickChart API
5. Full report emailed to the user

## ⚙️ Setup Instructions
1. Import workflow/data_analysis_workflow.json into n8n
2. Add credentials: Google Gemini API key, Gmail OAuth2
3. Activate the workflow and open the form URL

## 📸 Screenshots
### Workflow
![Workflow](screenshots/workflow_overview.png)

### Input Form
![Form](screenshots/input_form.png)

### Output Email
![Email](screenshots/output_email.png)

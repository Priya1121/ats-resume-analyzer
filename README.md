 ATS Resume Analyzer - n8n Workflow

This is a small hands-on project built in n8n to analyze resumes against job descriptions.

## Features
- ATS match score calculation
- Missing skills detection
- Weak bullet points detection
- Resume improvement suggestions
- Rewritten resume optimized for ATS

## How to use
1. Import `ats-resume-analyzer.json` into your n8n instance.
2. Make sure you have a Form Trigger node for uploading resumes and job descriptions.
3. Optionally, expose the workflow via a public webhook (ngrok or hosted n8n).

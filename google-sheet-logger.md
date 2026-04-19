# Google Sheet Logger

## Description
Formats all gathered intelligence into a clean JSON object for Google Sheets integration.

## Instructions
1. Collect data from previous skills.
2. Format as:
{
  "company": "[Name]",
  "tier": "[A/B]",
  "model": "[Selected Model]",
  "email_sent": "[Draft Content]",
  "status": "Lead Identified"
}
3. Use the `run_js` tool to push this data to the designated Google Apps Script URL.

# automation_utsavy_hiring

Simple plain HTML/JavaScript web app to upload a CSV and trigger outreach actions.

## Features
- Upload CSV with columns: `Name`, `Phone`, `Email`, `Role`
- Display data in a table
- Per-row **WhatsApp** button (opens `wa.me` with prefilled message)
- Per-row **Email** button (opens `mailto:` with subject + body)

## Run
Open this file directly in your browser:
- `/home/runner/work/automation_utsavy_hiring/automation_utsavy_hiring/index.html`

## CSV format
Example:

```csv
Name,Phone,Email,Role
Alice,+919999999999,alice@example.com,Frontend Developer
Bob,+919888888888,bob@example.com,Backend Developer
```

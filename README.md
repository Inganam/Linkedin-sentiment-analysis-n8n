# LinkedIn Sentiment Analysis Automation (n8n)

## Project Overview
This project demonstrates an automated workflow for analyzing public LinkedIn posts using AI-powered sentiment analysis. LinkedIn data is scraped using Apify, processed through n8n, analyzed for sentiment, and stored in Google Sheets. An automated report is generated, and key insights are sent via Slack.

## Tools Used
- Apify (LinkedIn data scraping)
- n8n (workflow automation and orchestration)
- Google Sheets (data storage and automated reporting)
- AI Sentiment Analysis (Groq AI)
- Slack (automated insight notifications)

## Project Features
- Scraping public LinkedIn post data using Apify
- AI-based sentiment classification (Positive, Neutral, Negative)
- Engagement analysis (likes, comments, reposts)
- Automated Google Sheets report
- Automated Slack insight summary

## Automated Report (Google Sheets)
The **Report** tab in Google Sheets includes:
- Average post sentiment
- Top 3 posts by engagement
- Summary of AI-processed insights

This tab serves as the project’s automated report output.

## Files in This Repository
- `AI LinkedIn scrape.csv` – Scraped and AI-processed LinkedIn post data
- `AI LinkedIn scrape workflow.json` – Exported n8n workflow
- `Spreadsheet.png` – Screenshot of the Google Sheets data
- `report.png` – Screenshot of the Google Sheets automated report
- `slack_notification.png` – Screenshot of the Slack insight message

## How the Workflow Runs
1. LinkedIn posts are scraped using Apify
2. Data is processed and sent to n8n
3. AI sentiment analysis is applied to post content
4. Results are stored and summarized in Google Sheets
5. Key insights are sent automatically to Slack

## Author
Inga Mbambo

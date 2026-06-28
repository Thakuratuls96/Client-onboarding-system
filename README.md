# 🚀 AI Client Onboarding Automation

An automated client onboarding workflow built with **Make.com** that uses **Google Gemini AI** to generate personalized welcome messages, creates onboarding PDFs, stores them in Google Drive, and emails clients automatically.

## Workflow

Google Sheets → Google Gemini AI → PDF.co → Google Drive → Gmail → Google Sheets

## Features

- Detects new client submissions
- Generates AI-powered welcome messages
- Sends an admin email if AI generation fails
- Creates onboarding PDFs with PDF.co
- Uploads PDFs to Google Drive
- Emails clients with the PDF attached
- Updates Google Sheets with the onboarding status

## Tech Stack

- Make.com
- Google Sheets
- Google Gemini AI
- PDF.co
- Google Drive
- Gmail
- google sheet

## Preview

> 📷 Visual representation of the Make.com automation scenario.

![Make Scenario Diagram](./assets/workflow-diagram.png)

## 🔄 Workflow Diagram

```text
Google Sheets
      │
      ▼
Google Gemini AI
      │
      ├── Success ───────────────┐
      │                          ▼
      │                     PDF.co
      │                          ▼
      │                    Google Drive
      │                          ▼
      │                        Gmail
      │                          ▼
      │                   Google Sheets
      │
      └── Failure
             ▼
      Admin Email Notification

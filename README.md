# Ken’s Job Tracker 2026 — v2

A simple, clean web app for tracking job applications — built for Ken, synced across all devices.

🌐 **Live app:** https://srgent23.github.io/ken-job-tracker/

-----

## What’s in the app

### 📋 Job Applications

Add and track every job Ken applies for. Each application stores:

- Company name and job title
- Date applied
- Current status (color coded)
- Which resume was sent
- Follow-up reminder date
- Notes (contact name, next steps, anything helpful)

### 🎯 Interview Prep (AI-powered)

Tap the 🎯 button on any job card to instantly generate 7 interview questions specific to that company and role. Ken can check off questions as he practices them to track his confidence.

### 🔔 Follow-Up Email Reminders

Set a follow-up date when adding a job. On that date, Ken automatically gets an email reminder at Richardsonjr.k@gmail.com reminding him to follow up with the company.

### 📄 Weekly PDF Report

Tap **Weekly Report** in the top right to download a PDF summary of that week’s applications — great for Ken to share with his dad to show his progress.

-----

## Status colors

|Color   |Status              |What it means              |
|--------|--------------------|---------------------------|
|🔵 Blue  |Applied             |Application submitted      |
|🟣 Purple|Waiting to hear back|No reply yet               |
|🟠 Orange|Interview scheduled |They want to meet!         |
|🟢 Green |Got an offer!       |Congratulations!           |
|🔴 Red   |Not selected        |They went another direction|

-----

## Ken’s resumes

The app has all 5 of Ken’s resumes built in as dropdown options:

|Version|Focus                   |
|-------|------------------------|
|V1     |Retail Sales            |
|V2     |Warehouse & Logistics   |
|V3     |Customer Service        |
|V4     |Facilities & Maintenance|
|V5     |Food Service & Grocery  |

-----

## How to use it

1. Open the app at https://srgent23.github.io/ken-job-tracker/
1. Tap **+ Add Job** to add a new application
1. Fill in company, job title, status, which resume you sent, and optionally a follow-up date
1. Tap **Save**
1. To practice for an interview, tap the 🎯 button on any job card
1. Every Sunday, tap **Weekly Report** to download the week’s PDF summary

-----

## How it works (technical)

|Part               |Tool                 |Cost            |
|-------------------|---------------------|----------------|
|App hosting        |GitHub Pages         |Free            |
|Database / sync    |Firebase Firestore   |Free            |
|Email reminders    |EmailJS              |Free (200/month)|
|Interview questions|Claude AI (Anthropic)|Free tier       |
|PDF export         |jsPDF                |Free            |

Data is stored in Firebase Firestore and syncs in real time across all devices — phone, tablet, and laptop all show the same jobs instantly.

-----

## Updating the app

To make changes, edit `index.html` directly on GitHub at:
https://github.com/srgent23/ken-job-tracker/edit/main/index.html

Changes go live at the app URL within about 60 seconds.

-----

*Built with care for Ken. Keep applying — you’ve got this! 💪*
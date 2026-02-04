🚀 Overview

This project automates bill/invoice generation and email delivery using a workflow automation tool.

When executed, the system:

Reads customer/order data from Google Sheets

Generates PDF invoices using PDFMonkey

Sends the generated PDF automatically via Gmail

✅ Fully automated
✅ Saves time
✅ Reduces human errors

🧩 Workflow Architecture
Trigger → Read Sheet → Generate PDF → Send Email

Steps Explained
1️⃣ Trigger – Execute Workflow

Manual or scheduled execution

Starts the automation

2️⃣ Google Sheets – Get Rows

Reads billing/customer details from sheet.


3️⃣ PDFMonkey – Generate Document

Creates dynamic PDF invoice

Uses sheet data to fill template

Output: downloadable invoice PDF

4️⃣ Gmail – Send Message

Sends email to customer

Attaches generated invoice

Subject: Invoice/Bill

Body: Payment details

📊 Data Flow Diagram
Google Sheet Data
       ↓
 PDF Template Generation
       ↓
 Invoice PDF
       ↓
 Email to Customer


🛠️ Tech Stack
Tool	Purpose
Google Sheets	Data source
PDFMonkey	PDF invoice generation
Gmail API	Email sending
Workflow Automation - n8n


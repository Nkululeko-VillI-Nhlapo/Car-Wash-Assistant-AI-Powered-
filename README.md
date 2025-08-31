# Car-Wash-Assistant-AI-Powered-
# 🚘💦 MR Banks Car Detailing Assistant (AI-Powered)

Your **AI-driven WhatsApp Business Assistant** for managing a car detailing business in South Africa 🇿🇦.  
This project integrates **Claude AI 🤖, Twilio WhatsApp API 📱, and Google Drive Sheets 📊** to automatically:

- 📥 Log services and expenses from natural WhatsApp messages  
- 💰 Track revenue, expenses, and profit margins  
- 📊 Generate instant reports & financial insights  
- 👨‍👩‍👧 Analyze customer journeys (new vs repeat customers)  
- 🕒 Provide South African date/time & weekly breakdowns (1–4 per month)  

---

## ✨ Features

- **AI-Powered WhatsApp Assistant** (via Anthropic Claude + Twilio)  
- **Smart Service Logging** (Customer, Service Type, Amount, Payment Method, Status)  
- **Expense Tracking** (Amount, Supplier, Category)  
- **Business Intelligence Reports** (profitability, payment rate, best service, customer insights)  
- **South African Context** (Rand 💵, UTC+2 timezone, week-of-month tracking)  
- **Google Drive Integration** (syncs Excel workbook for Operations, Revenue & Expenses)  
- **Cash Flow & Income Statements** (on-demand via chat)  
- **Conversational Data Collection** ("Moloi, who was the customer?", "How much did you spend?")  

---

## 🛠️ Tech Stack

- **Backend Framework**: Flask  
- **AI/LLM**: Anthropic Claude  
- **Messaging**: Twilio WhatsApp API  
- **Data Storage**: Google Drive Sheets (Excel)  
- **Data Processing**: openpyxl  
- **Logging & Monitoring**: Python `logging`  

---

## The **Excel Workbook** in Google Drive contains three main sheets:

- `Operations` ➝ Tracks services completed  
- `Revenue` ➝ Tracks payments and status  
- `Expenses` ➝ Tracks business expenses  

---

## 💬 WhatsApp Interaction

Examples of what you can send to the bot:

📌 Log a service:

Customer John did a full wash today and paid R180 by card


➡️ AI logs service into Operations + Revenue sheets automatically

📌 Log an expense:

Paid R350 for new soap from CleanSupplies


➡️ AI logs expense into Expenses sheet

📌 Request a report:

Moloi, show me business performance this week


➡️ AI generates instant profitability & performance summary

📌 Ask finance terms:

Moloi, explain profit margin


➡️ AI explains in simple business English

📊 Sample Reports

📈 Enhanced Business Report

"Business is profitable, Moloi. Revenue R12,500, expenses R5,200. You made R7,300 profit. Payment rate: 92% (R11,500 collected). Your best service is Premium Wash with R4,200 from 15 jobs. You served 38 customers, 12 came back. Focus on collecting payments – some customers still owe money."

📉 Cash Flow Report

"Cash flow is positive, Moloi. R15,000 coming in, R6,000 going out. Net cash flow: R9,000."



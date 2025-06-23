# 🤖 WhatsApp Chatbot for Citizen Requests – n8n Workflow

## 📌 Overview

This is an automated WhatsApp chatbot built with **n8n** to manage citizen requests using interactive buttons.  
It receives messages, identifies the user, and stores the interaction details in **Google Sheets** for tracking and follow-up.

---

## ⚙️ What the Workflow Does

- Listens for incoming messages via **WhatsApp Webhook**
- Greets the user with **interactive button options**:
  - “Create report”
  - “Check report”
- Captures:
  - Phone number
  - Name
  - Button selection
  - Timestamp
- Stores and updates the data in a **Google Spreadsheet**
- Handles new vs existing users and updates view counts

---

## 🛠️ Tools Used

- [n8n](https://n8n.io/) – Workflow automation platform
- **WhatsApp Business API**
- **Google Sheets integration**
- Logic nodes: `If`, `Switch`, `Set`, `Code`

---

## ▶️ How to Use

1. Open your **n8n instance**.
2. Click on `Import` and upload the file:  
   `chatbot_WhastApp.json`
3. Replace credentials:
   - WhatsApp API token
   - Google Sheets document ID and sheet names
4. Customize the message text and logic if needed.
5. **Activate** the workflow and test it with a messaging platform (e.g. WhatsApp via Meta API or Twilio).

---

## 📂 File Included

- `chatbot_WhastApp.json` – Full exported workflow (ready to import into n8n)

---

## 🙋 About the Author

Built by **Santiago Cheluja**, Data Engineering student at Universidad del Caribe.  
Focused on building useful, real-world automations with open source tools and civic technology.

- LinkedIn: [https://linkedin.com/in/your_profile](https://linkedin.com/in/your_profile)

---

# 📧 AI-Powered Email Assistant using n8n + Gemini (or any LLM)

![n8n](https://img.shields.io/badge/Built%20with-n8n-orange?logo=n8n&logoColor=white)
![LLM](https://img.shields.io/badge/Powered%20by-Gemini%20(or%20Any%20Model)-blueviolet)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-brightgreen)
![No Code](https://img.shields.io/badge/No%20Code-Low%20Code-green)
![Automation](https://img.shields.io/badge/Category-Email%20Automation-lightgrey)

A smart and **completely customizable AI-based Email Assistant** built with [n8n](https://n8n.io). This automation reads your emails, categorizes them using an LLM (Gemini or any you choose), analyzes the intent, and drafts or sends personalized replies — all with just one-click setup!

---

## 📦 Features

- **Multi-category Email Sorting:** App Users, Customers, Others — and add more as you need
- **LLM-Powered Reply Generation:** Analyze message intent (question, error, suggestion, etc.)
- **Auto-draft or Auto-send Emails:** Choose full automation or manual control
- **Model Agnostic:** Use Gemini, OpenAI, Claude, Mistral, or any text-capable LLM
- **Business Ready:** Ideal for solopreneurs, startups, and anyone who receives lots of emails
- **Zero code changes needed after setup**

---

## 📁 Folder Structure

```plaintext
/email-assistant-automation/
├── workflow.json               # Your exported n8n workflow file
├── README.md                   # This documentation file
├── screenshots/                # Add screenshots of your n8n flow here
└── assets/                     # Optional: icons, prompts, config

```

---

## 🛠️ Setup Guide

### 1. 📥 Import Workflow
- Download the `.json` file from this repo
- In your n8n instance: **Import → Workflow File**

### 2. 🔐 Configure Email Access
- Add your email credentials (IMAP & SMTP) to n8n
- Supports Gmail, Outlook, Yahoo, Zoho, and more

### 3. 🧠 Setup Your LLM
- Use [Google Gemini](https://deepmind.google/technologies/gemini/) or [OpenAI](https://platform.openai.com/)
- Update the **AI node** with your API key & URL

### 4. 🧠 Customize Prompt Logic (Optional)
You can enhance the prompt to:
- Detect bug reports
- Answer product questions
- Suggest features
- Reply in a defined tone (formal, friendly, etc.)

---

## ⚙️ How It Works

1. Fetches unread emails
2. Sends the content to LLM
3. Categorizes (App User, Customer, Other)
4. Generates meaningful, prompt-based replies
5. Saves a **draft** or **auto-sends**
6. Logs every reply for record-keeping

---

## 🤓 Learning Outcomes

✅ Understand how to use AI to automate real-world business operations  
✅ Learn LLM prompting for categorized actions  
✅ Build professional automation workflows with zero/minimal code  
✅ Work with IMAP, SMTP, and HTTP Request nodes in n8n  
✅ Add logic branches based on categorized analysis  

---

## 💡 Use Cases

- 💼 Business owners managing leads and clients
- 🧑‍💻 Developers getting app feedback from users
- 📨 Freelancers handling a full inbox
- 🧠 Productivity hackers creating an AI-powered inbox

---

## ⭐ Show Your Support

If this helped you save time or taught you something new:

🌟 **Star this repo**  
👀 **Watch for updates**  
📥 **Follow [@ZubairAlltaf](https://github.com/ZubairAlltaf)** for more unique n8n automations

---

## 🙋 Questions or Suggestions?

Feel free to [open an issue](https://github.com/ZubairAlltaf) or reach out — let’s grow this automation together 💌

---

### 🔗 Want more?

Check out my full [Automation Hub](https://github.com/ZubairAlltaf?tab=repositories) for more awesome projects!

```

---

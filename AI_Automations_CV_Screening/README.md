# 🚀 Day 45/100 – AI Automations: Automated CV Screening with AI  

This project is part of my **100 Days of AI Automations** challenge.  
Here, we automate **CV screening** with the power of **n8n**, **Mistral AI OCR**, and **SambaNova’s GPT-OSS 120B** hosted model.  

---

## 🔹 Workflow Overview  
**Workflow Name:** Automated CV Screening  

**Stack Used:**  
- **n8n** – Workflow automation platform  
- **Mistral AI OCR** – Extract text from uploaded CVs (PDF/DOC)  
- **SambaNova GPT-OSS 120B** – AI model for evaluation  
- **Google Sheets** – Store candidate results  

---

## ⚡ How It Works  

1️⃣ **Collect CVs** via a form (Google Forms, Typeform, or any connected service)  
2️⃣ **Extract text** using **Mistral AI OCR** node  
3️⃣ **Evaluate candidates** against job requirements using **SambaNova GPT-OSS 120B**  
4️⃣ **Store results** → Output a **qualification score + AI-generated explanation** into **Google Sheets**  

---

## ✅ Problem It Solves  
Recruiters and HR teams spend hours manually screening CVs.  
This automation:  
- Speeds up the process  
- Ensures **structured & transparent evaluations**  
- Reduces **bias & inconsistency**  
- Saves **time & effort**  

> I even tested it on my own CV for a **Data Analyst role in Copenhagen** — results were **spot on**! ⚡  

---

## ☁️ Why GPT-OSS 120B on SambaNova?  

🔹 **Speed** → 700+ tokens/sec 🚀  
🔹 **Compliance** → US-built, open-source (Apache 2.0), ensuring full ownership & control  
🔹 **Value** → Lower cost ($0.22 / $0.59) vs. closed-source alternatives  
🔹 **Flexibility** → Fine-tune with your own data, deploy anywhere, and stay secure  

---

## 🛠️ Setup Guide  

1. Clone this repo or copy the workflow JSON file into your **n8n instance**.  
   ```bash
   git clone https://github.com/martinkhristi/n8n_automations_magic.git
   cd n8n_automations_magic/AI_Automations_CV_Screening
🎥 Demo Video

Watch the full step-by-step demo here:
https://youtu.be/8Q_e0SzHj_8?si=qCD802PlVYhJsDAY
AI_Automations_CV_Screening/
│── workflow.json      # n8n workflow file
│── README.md          # This guide

🌍 Join the Journey
This is Day 45/100 of my 100 Days of AI Automations.
Follow along for daily projects → AI + Automation + Real-world impact.

💡 Community ideas + SambaNova’s power = real-world solutions.



📌 Example Workflow: SambaNova WhatsApp Agent

This workflow turns WhatsApp into your personal AI assistant powered by SambaNova’s Llama-4 Maverick model.

🔹 Features

Two-way WhatsApp integration (send & receive messages)

AI-powered responses with SambaNova Llama-4 Maverick

Conversation memory for context-aware replies

Google Calendar integration → ask “How’s my day?” and get your events back in WhatsApp

⚙️ Workflow Steps

WhatsApp Trigger – Listens for new messages.

SambaNova Chat Model – Runs AI response with Llama-4 Maverick.

Simple Memory – Keeps conversation context.

Google Calendar Tool – Fetches events.

SambaNova Agent – Orchestrates AI + tools.

Send Message – Replies back in WhatsApp.

🚀 Use Cases

Daily schedule updates in WhatsApp

AI assistant for customer support

Personal productivity agent

Demos for clients

🔧 WhatsApp Setup (Quick Guide)

Go to Meta Developers
 → Create App (Business).

Add WhatsApp as a product.

Copy your Client ID, Client Secret, and Access Token.

Register your phone number.
.

📂 Getting Started

Clone this repo:

git clone https://github.com/martinkhristi/n8n_automations_magic.git


Import SambaNova_whatsapp_Agent.json into n8n.

Add credentials:

WhatsApp Business API (Client ID, Secret, Token)

SambaNova API

Google Calendar OAuth

Activate → start chatting with your AI-powered WhatsApp agent.
Add Webhook URL + Verify Token from n8n.

Test → workflow is live.

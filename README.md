🚀 Automated Email Workflow with n8n & Forms

This project demonstrates how to build an AI-powered automation using n8n that:

Captures user input from a form submission.

Uses an AI model (Gemini / ChatGPT) to generate a personalized email.

Automatically sends the email to the recipient via an email service (SMTP, Gmail, or Outlook).

🔹 Features

📋 Form Integration – Triggered whenever a user submits a form.

🤖 AI-Powered Email Composition – Dynamic email drafting using Gemini or OpenAI.

📧 Automated Sending – Emails are sent automatically through the configured email node.

🔄 No Code / Low Code – Entire workflow built in n8n, no heavy coding required.

🔑 Customizable – Change prompt, email template, or target service easily.

🔹 Tech Stack

n8n
 – Workflow automation

Google AI Gemini API (or OpenAI) – AI text generation

Email Service – SMTP / Gmail / Outlook

🔹 Use Cases

Lead nurturing emails after form submissions

Automated customer onboarding emails

Personalized responses based on form data

AI-driven business communication

🔹 How It Works

User fills in the form (name, email, service, etc.).

Form trigger node in n8n captures the data.

AI model generates a professional, context-aware email.

Email node sends it automatically to the user.

🔹 Getting Started

Clone this repo

Import the workflow JSON into n8n

Add your API keys (Gemini / OpenAI + Email Service)

Deploy & test 🎉

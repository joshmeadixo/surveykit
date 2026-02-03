# surveykit

**A lightweight, in-app micro-survey and announcement engine for Next.js apps.**  
JSON-configured. Client-side targeting. Store responses anywhere.

SurveyKit lets you add in-app surveys, announcements, and feedback prompts
(NPS, CSAT, free-text feedback) without relying on a hosted SaaS.

---

## ✨ Features

- 📦 **Next.js / React friendly**
- 🧩 **JSON-based survey definitions**
- 🎯 **Client-side targeting & triggers**
- 🔁 **Frequency caps & cooldowns**
- 🧠 **Event-based prompts**
- 🎨 **Built-in UI components (modal, banner)**
- 🔓 **Open source & self-hosted friendly**
- 📡 **Send responses anywhere (your API, PostHog, webhooks, DB, etc.)**

---

## 🧠 How it works

1. You define surveys using JSON (locally or from your API)
2. SurveyKit evaluates targeting rules in the browser
3. When a survey is eligible, it renders the UI
4. Responses are sent to a handler you control

No hosted backend required.

---

## 🚀 Installation

```bash
npm install surveykit

# 🚀 LinkedIn AI Automation using Zapier

## 📌 Overview

This project automates the process of generating and posting LinkedIn content using AI.

It uses **Zapier**, **Groq (LLM)**, and **Google Sheets (memory system)** to create a fully automated workflow that:

* Generates AI-powered LinkedIn posts daily
* Avoids repeating topics using stored memory
* Automatically publishes posts to LinkedIn

---

## 🧠 Key Idea

> Build a **self-learning AI content system** that improves over time by remembering past posts.

---

## ⚙️ Workflow Architecture

```
Schedule → Fetch Previous Posts → AI Generation → Save to Memory → Post to LinkedIn
```

---

## 🔄 Step-by-Step Workflow

### 1️⃣ Schedule Trigger (Zapier)

* Runs **once every day**
* Initiates the automation

---

### 2️⃣ Fetch Previous Posts (Google Sheets)

* Retrieves last **10 previously generated posts**
* Acts as **memory**
* Helps avoid duplicate or similar topics

---

### 3️⃣ AI Content Generation (Groq)

* Uses LLM (`llama-3.3-70b-versatile`)
* Receives:

  * Previous posts (memory)
  * Instructions to avoid repetition
* Generates:

  * A fresh, engaging LinkedIn post
  * Trending topic in AI/ML/software development

---

### 4️⃣ Store New Post (Google Sheets)

* Saves generated post into sheet:

  * 📅 Date
  * 🧠 Topic (AI output)
  * 📝 Full Post
* This becomes memory for future runs

---

### 5️⃣ Post to LinkedIn

* Automatically publishes the generated content
* Fully hands-free posting

---

## 🧾 Google Sheets Structure

| Date        | Topic      | Post               |
| ----------- | ---------- | ------------------ |
| Apr 6, 2026 | AI Agents  | Full LinkedIn Post |
| Apr 7, 2026 | LLM Trends | Full LinkedIn Post |

---

## 🛠 Tech Stack

* ⚡ Zapier (Automation)
* 🧠 Groq API (LLM - AI content generation)
* 📊 Google Sheets (Memory storage)
* 💼 LinkedIn API (via Zapier)

---

## 🔥 Features

* ✅ Fully automated LinkedIn posting
* 🧠 Memory-based topic generation (no repetition)
* 🤖 AI-generated high-quality content
* ⏰ Scheduled daily execution
* 🔄 Self-improving system

---

## ⚠️ Limitations

* Zapier Free Plan:

  * Limited tasks/month (~100)
* Basic topic extraction (can be improved)

---

## 🚀 Future Improvements

* 🔍 Extract only topic instead of full post (clean memory)
* 📈 Add trending topic API (Twitter/Reddit)
* 🌐 Multi-platform posting (Twitter, Instagram)
* 🧩 Migrate to n8n for unlimited automation
* 📊 Analytics dashboard for post performance

---

## 📸 Screenshots

*Add your Zapier workflow screenshots here*

---

## 💡 Use Case

* Personal branding automation
* Content creators
* Developers sharing daily insights
* AI enthusiasts building agentic systems

---

## 🧑‍💻 Author

**Sabari M**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to fork!

---

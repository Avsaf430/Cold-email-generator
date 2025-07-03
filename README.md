# 🤖 AI-Powered Cold Email Generator 

🚀 **A powerful and production-ready tool that leverages the latest in LLM technology to generate personalized cold emails from job links — built with LangChain, Groq, and LLaMA 3.**

---

## 📜 Story Behind the Project

In today’s competitive job market, personalized outreach is key to getting noticed. As an AI engineer passionate about NLP and automation, I built this cold email generator to help professionals craft **job-specific outreach emails** at scale using **Groq's blazing fast inference** capabilities and LangChain's modular LLM chaining framework.

Whether you're reaching out to a recruiter, company, or hiring manager — this project simplifies the process and delivers high-quality, human-like cold emails from just a job posting link.

---

## 💼 Use Case Scenario

🔹 Imagine you're browsing LinkedIn or Indeed and find a role you'd love to apply for.  
🔹 Instead of manually writing a cold email, you input the **job posting link** into this tool.  
🔹 The AI reads and understands the role, company, and responsibilities using a smart prompt chain.  
🔹 It generates a **concise, customized cold email** tailored to the job — saving time and improving outreach efficiency.

---

## 🔁 System Architecture

To visualize the flow, here's the end-to-end architecture of the solution:

![System Architecture](architecture.png)

---

## ⚙️ Project Flow

1. **🔗 Input Job Link** – Paste a link to the job posting.
2. **🤖 LangChain with Groq API** – Uses `llama-3-70b` from Groq for fast and intelligent text generation.
3. **📧 Cold Email Output** – A ready-to-send, context-aware, professional cold email.

---

## 🧠 Tools & Technologies Used

| Tech Stack       | Purpose |
|------------------|---------|
| 🐍 Python         | Core programming language |
| 🧠 LangChain      | LLM chaining and prompt engineering |
| ⚡ Groq API       | Fast inference using LLaMA 3-70B |
| 🧪 dotenv         | Secure API key management |
| 📓 Jupyter Notebook | Experimentation and development environment |

---

## 🧰 Requirements

Install the required dependencies:

```bash
pip install langchain-groq python-dotenv

<h1 align="center">Hi, I'm Parth Pungle 👋</h1>

<p align="center">
  <b>Full-Stack & AI Developer</b> — I build LLM-powered apps, ML services and cloud tooling, end to end.<br/>
  📍 Bengaluru, India
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/parth-pungle-712a70314/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <!-- Add your email and uncomment:
  <a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  -->
  <a href="https://github.com/parthpungle?tab=repositories"><img src="https://img.shields.io/badge/Projects-View_All-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"/></a>
</p>

---

## 🚀 About Me

- 🧠 I build **applied AI that people can trust** — e.g. LLM agents that call deterministic tools instead of guessing numbers.
- 🛠️ I work across the stack: **Python (FastAPI, Flask)**, **TypeScript (Express, React)** and **Java**, backed by **PostgreSQL** and **MongoDB**.
- ☁️ I've shipped cloud-integrated systems on **Google Cloud** with real-time dashboards, ML anomaly detection and automated remediation.
- 🤝 I build well in teams — two of my featured projects are multi-service systems delivered with teammates, one for a 2026 hackathon.
- 🎯 **Open to** software engineering and AI/ML engineering opportunities.
<!-- - 🎓 Studying [Degree] at [College], graduating [Year] -->

---

## ⭐ Featured Projects

### 🎙️ [FinPal — Voice-First AI Financial Advisor](https://github.com/parthpungle/FinPal-Student-financial-advisor)
A conversational finance assistant you can talk to by voice or text. It collects your income, expenses, debts and goals — then gives **computed, grounded advice, not hallucinated numbers.**

- Designed an **LLM orchestration loop with tool calling**: the model drives the conversation but never does arithmetic — every figure comes from a **deterministic rules engine** of 10 calculators (50/30/20 budgeting, SIP projections, EMI affordability, avalanche/snowball debt payoff, FI number, BNPL-risk audit and more).
- Built **real-time voice**: in-browser audio capture → Whisper speech-to-text → spoken replies via text-to-speech, with token streaming over **Server-Sent Events**.
- **Pluggable LLM providers** (Groq, OpenRouter, Gemini) switched by a single config value; session profiles persisted with SQLAlchemy on PostgreSQL/SQLite.
- Accessible, framework-free frontend with a live dashboard that fills in as the conversation progresses.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![LLM Tool Calling](https://img.shields.io/badge/LLM-Tool_Calling-6B4FBB?style=flat-square)
![Whisper](https://img.shields.io/badge/Speech-Whisper-412991?style=flat-square)

---

### ☁️ [CloudSnip — Cloud Cost Intelligence](https://github.com/parthpungle/CloudSnip) · *Team project, Hackathon 2026*
A platform that watches a live Google Cloud project, spots cost anomalies with ML and **fixes them automatically**.

- Telemetry pipeline pulls monitoring, billing and inventory data every 5 minutes into MongoDB Atlas.
- **Isolation Forest** anomaly detection served as a separate Python/Flask microservice.
- Auto-remediation via GCP APIs — stops idle VMs, caps runaway Cloud Functions, deletes orphan disks — with **approve / reject / rollback** for every action.
- Plain-English explanations of each anomaly, Slack alerts, and a React 19 dashboard updated live over **Socket.IO** (cost trends, heatmap, what-if simulator, compliance score).

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

---

### 📦 [TraceChain — Supply Chain Provenance System](https://github.com/parthpungle/tracechain) · *Team project*
A full-stack, **3-tier** platform that traces where every part of a product came from.

- **Recursive SQL** queries resolve a finished product's full component tree for provenance tracing.
- Chain-of-custody tracking of batches across warehouses, plus supplier compliance status (RoHS, ISO).
- Java REST API (Spark framework, JDBC) over a 9-table PostgreSQL schema; React + Vite + Tailwind dashboard.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

### 📷 [Image Caption Generator (Offline)](https://github.com/parthpungle/Image_caption_generator)
Generates natural-language captions for any image using Salesforce's **BLIP** vision-language model — running **100% locally on CPU**, with no API keys or usage costs.

- Streamlit web UI with optional guided prompts to steer the caption.
- One-time model download, then fully offline inference.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

## 🧰 Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**AI / ML**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LLM Agents](https://img.shields.io/badge/LLM_Agents_&_Tool_Calling-6B4FBB?style=flat-square)
![Speech](https://img.shields.io/badge/Speech_(STT_/_TTS)-412991?style=flat-square)

**Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Data & Cloud**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📫 Let's Connect

I'm always happy to talk about AI products, full-stack engineering or a role you're hiring for.
**[Connect on LinkedIn →](https://www.linkedin.com/in/parth-pungle-712a70314/)**

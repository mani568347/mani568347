<div align="center">

# <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=32&duration=3500&pause=600&color=7EE8FA&center=true&vCenter=true&width=520&lines=Chinnapondara+Manikanta;Python+%7C+Django+%7C+AI%2FML+Engineer;I+build+AI-powered+automation;and+Intelligent+Web+Applications" alt="Typing headline" />

**AI / ML Engineer · Python · Django · Retrieval-Augmented Generation · Intelligent Automation**

<br/>

[![Visitors](https://komarev.com/ghpvc/?username=mani568347&color=7EE8FA&style=flat-square&label=PROFILE+VISITS)](https://github.com/mani568347)

</div>

---

## About Me

Hi, I'm **Chinnapondara Manikanta** — an AI/ML-focused developer who builds practical, production-shaped systems with Python. My work sits where **applied machine learning meets everyday automation**: RAG chatbots that answer only from vetted documents, an agent that hunts job listings while you sleep, and a fine-tuned BERT system that verifies news in real time.

I care about systems that are **honest and defensible** — licensed data sources over scraping, structured model outputs over free-form prose, real citations over confident guesses. Every project below is documented end-to-end with its architecture, security posture, and setup steps.

<div align="center">

### What I build

`Python` `Django` `RAG` `PyTorch / BERT` `AI Agents` `CI/CD Automation` `APIs` `OCR`

</div>

---

## Tech Stack

**Languages & Core**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff&style=flat-square)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff&style=flat-square)

**Backend & Web Frameworks**

![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=fff&style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=fff&style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff&style=flat-square)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=fff&style=flat-square)

**Machine Learning & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=fff&style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?logo=huggingface&logoColor=000&style=flat-square)
![BERT](https://img.shields.io/badge/BERT-181717?logo=huggingface&style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=fff&style=flat-square)
![Tesseract OCR](https://img.shields.io/badge/Tesseract%20OCR-5C6BC0&style=flat-square)

**RAG & Retrieval**

![ChromaDB](https://img.shields.io/badge/ChromaDB-277DDB&style=flat-square)
![BM25](https://img.shields.io/badge/BM25-3178C6&style=flat-square)
![Reranking](https://img.shields.io/badge/Cross--Encoder%20RRF-8250DF&style=flat-square)

**Generative AI & Agents**

![Gemini](https://img.shields.io/badge/Gemini-8E75B2?logo=googlegemini&logoColor=fff&style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036&style=flat-square)
![Pydantic AI](https://img.shields.io/badge/Pydantic%20AI-6C5CE7&style=flat-square)
![RapidAPI](https://img.shields.io/badge/RapidAPI%20JSearch-0097FF&style=flat-square)

**Automation, DevOps & Messaging**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=fff&style=flat-square)
![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=fff&style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff&style=flat-square)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?logo=twilio&logoColor=fff&style=flat-square)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?logo=googlesheets&logoColor=fff&style=flat-square)

---

## Featured Projects

<div align="center">

[![morning-job-agent](https://github-readme-stats.vercel.app/api/pin/?username=mani568347&repo=morning-job-agent&theme=tokyonight&hide_border=true)](https://github.com/mani568347/morning-job-agent)
[![RAG-coaching-centre-chatbot](https://github-readme-stats.vercel.app/api/pin/?username=mani568347&repo=RAG-coaching-centre-chatbot&theme=tokyonight&hide_border=true)](https://github.com/mani568347/RAG-coaching-centre-chatbot)
[![VeriTruth](https://github-readme-stats.vercel.app/api/pin/?username=mani568347&repo=VeriTruth&theme=tokyonight&hide_border=true)](https://github.com/mani568347/VeriTruth)

</div>

### 🧭 Morning Job Agent
An autonomous, cron-driven job-search agent. It fetches live listings via a licensed API, scores each against a resume with Gemini (Pydantic-validated 0–100 output), shortlists the top matches, drafts honest cover letters, and commits a daily report — all in GitHub Actions, with a hard monthly request budget and cross-run dedupe. **No scraping, no secrets in the repo.**

**Stack:** Python 3.12 · Pydantic AI · Gemini Flash · JSearch/RapidAPI · GitHub Actions

### 🎓 CodeCraft Academy RAG Chatbot
A retrieval-augmented chatbot that answers **only** from five official PDFs and cites the exact source file + page for every answer. Implements the full pipeline explicitly — Docling PDF parsing, ~200-token section-aware chunking, Gemini embeddings, ChromaDB, BM25, reciprocal-rank fusion, and a bge-reranker, with a strict refusal path for unsupported questions.

**Stack:** Docling · ChromaDB · BM25 · bge-reranker · Gemini · Streamlit

### 📰 VeriTruth — News Verification
An AI news-verification app. Submits text, URL, or image; a **fine-tuned BERT** classifier returns a REAL/FAKE verdict, backed by analysis signals, a Groq-generated explanation, and a contextual follow-up assistant. Includes Django auth, Google login, and an admin dashboard.

**Stack:** Django 5.2 · PyTorch/BERT · Tesseract OCR · Groq · MySQL

---

### More Projects

| Project | Description | Stack |
|---|---|---|
| [Telegram Clinic Appointment Booking](https://github.com/mani568347/Telegram-Clinic-Appointment-Booking) | Automated clinic appointment booking via a Telegram bot, an n8n workflow, and Google Sheets storage with automatic patient confirmation | n8n · Docker · Telegram · Cloudflare Tunnel |
| [Face Recognition Door Lock System](https://github.com/mani568347/door-lock-system-project) | Face-recognition door security with a desktop UI, MongoDB-backed access logs, and Twilio SMS alerts | OpenCV (LBPH) · MongoDB · Twilio · Tkinter |

---

## GitHub Analytics

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mani568347&show_icons=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=7EE8FA&icon_color=7EE8FA&text_color=c9d1d9&ring_color=7EE8FA)](https://github.com/mani568347)

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=mani568347&theme=github-dark&hide_border=true)](https://github.com/mani568347)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mani568347&layout=compact&hide_border=true&bg_color=0d1117&title_color=7EE8FA&text_color=c9d1d9)](https://github.com/mani568347)

</div>

### Contribution Activity

[![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=mani568347&theme=react-dark&hide_border=true&bg_color=0d1117&color=c9d1d9&line=7EE8FA&point=7EE8FA&area=true&area_color=7EE8FA&hide_title=false&title_color=7EE8FA)](https://github.com/mani568347)

---

## Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=fff&style=flat-square)](https://github.com/mani568347)

</div>

*Open to collaboration on AI/ML, automation, and full-stack Python projects.*

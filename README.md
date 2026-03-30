<div align="center">

# Akshat Malik

**Frontend and Backend Engineer · GenAI Developer · B.Tech CSE @ BIT Mesra**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshat-malik-2079973a0/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:akshat.malik.dev@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/akshatmalik-bruh)
[![Portfolio](https://img.shields.io/badge/Portfolio-akshatmalik--github--io.vercel.app-000000?style=flat-square&logo=vercel&logoColor=white)](https://akshatmalik-github-io.vercel.app)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/akshaaaaattttt)
[![Open to Work](https://img.shields.io/badge/Open%20to%20Work-Backend%20%7C%20GenAI-22c55e?style=flat-square&logo=briefcase&logoColor=white)](#)

</div>

---

## About

I'm a final-year Computer Science student at BIT Mesra (CGPA: 8.18) with a focus on building backend systems that are reliable, scalable, and intelligent. My work sits at the intersection of **distributed systems**, **LLM integration**, and **API design** — I care about software that actually works in production, not just in demos.

Currently looking for **Software Engineering / Backend / GenAI roles** where I can contribute to systems that handle real scale and complexity.

---

## Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**AI / LLMs**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq%20%28Llama%203%29-F55036?style=flat-square&logo=meta&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Databases & Caching**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Projects

### [AI README Generator](https://github.com/akshatmalik-bruh/ReadMe-file-generator)
> Generates intelligent GitHub READMEs from repository data using LLMs

Pulls repository metadata via **Octokit**, feeds it to **Llama 3 (Groq)** for context-aware content generation, and caches results with **Redis** to minimize redundant API calls. Designed to handle varied repo structures gracefully.

`Node.js` `Groq` `Llama 3` `Octokit` `Redis`

---

### [Virtual Money Transfer System](https://github.com/akshatmalik-bruh/virtual_money_transfer)
> Fintech-grade transaction engine with ACID guarantees

Built around **atomic transactions** and **MongoDB sessions** to ensure data consistency under concurrent load. Backend APIs handle balance management, transfers, and rollback logic — modeled on patterns used in real payment systems.

`Node.js` `Express` `MongoDB` `ACID Transactions` `Web Poling`

---

### [Snap Stream](https://github.com/akshatmalik-bruh/snap-stream)
> Turns YouTube videos into structured, readable summaries

Extracts audio and transcript data using **yt-dlp**, runs summarization through **locally hosted LLMs via Ollama** (no external API cost), and persists results in **PostgreSQL** for retrieval. Fully self-contained pipeline.

`FastAPI` `Python` `Ollama` `yt-dlp` `PostgreSQL`

---

### [Resume Analyzer](https://github.com/akshatmalik-bruh/resumeAnalyser)
> Multi-LLM resume optimization tool

 Automatically parses PDF resumes and extracts core skills, experiences, and qualifications.
- **Intelligent ATS Scoring**: Computes a compatibility score (ATS Score) between the user's resume and a target job description, identifying critical gaps.
- **Comprehensive Interview Reports**: Generates detailed reports including potential interview questions, behavioral insights, and tailored advice to help candidates prepare.
- **Dynamic Resume Optimization**: Goes beyond analysis by using AI to generate a restructured, optimized PDF resume that highlights the most relevant skills for a specific job.
- **Smart Caching System**: Optimizes performance and reduces API costs by caching previous analyses and generated documents in a MongoDB database.
- **Secure Authentication**: Built-in user management system with JWT-based authentication to ensure private and secure storage of resumes and reports.

`Express` `MongoDB` `Gemini API` `Groq` `JWT` `Bcrypt` `PDF-Parse` `Puppeteer` `React + Vite` `Multer`

---

### [CP Extension](https://github.com/akshatmalik-bruh/CPextension)
> Browser extension for competitive programmers

Gives the space complexity , time complexity and optimal solution if required , also returns an explanation for the approach. Made for Leetcode and CodeForces

`JavaScript` `Manifest v3` `LLM Integration` `Redis` `Rate-Limiting`

---

## Research

**Youth Standpoints on Food Wastage at Indian Weddings**

Quantitative study examining awareness and behavioral patterns around food waste at Indian social events. Proposed a **Smart Food Distribution Platform** to bridge the gap between surplus food at events and nearby distribution networks, focusing on real-time logistics between donors and recipients.

[📄 Read Publication →](https://drive.google.com/file/d/1FgbL2TuScu7BhsIsuyZh-BFhnWWmKmVC/preview)

---

## What I'm Looking For

I'm interested in roles where the technical problems are genuinely hard — distributed systems that need to stay consistent, AI pipelines that need to be reliable in production, APIs that need to scale. I learn fast, care about the details, and prefer working on things that matter.

If you're building something in that space, I'd like to talk.

📧 [akshat.malik.dev@gmail.com](mailto:akshat.malik.dev@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/akshat-malik-2079973a0/) · 🌐 [Portfolio](https://akshatmalik-github-io.vercel.app)

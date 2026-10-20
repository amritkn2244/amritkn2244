<p align="center">
  <img src="header.svg" alt="Amrit Kumar Nayak - Python. DSA. AI. | Building in Public" width="100%"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/amritkn2244"><img src="https://img.shields.io/badge/LinkedIn-amritkn2244-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/amritkn2244/"><img src="https://img.shields.io/badge/LeetCode-amritkn2244-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/></a>
  <a href="https://x.com/amritkn2244"><img src="https://img.shields.io/badge/X-follow%20my%20journey-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
  <a href="mailto:amritkn2244@gmail.com"><img src="https://img.shields.io/badge/Email-amritkn2244%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

## 👋 Hey, I'm Amrit

- 🎓 4th-year B.Tech CSE student at Government College of Engineering, Keonjhar (2023 – 2027), Bhubaneswar, India
- 🧠 I build LLM apps and **measure whether they're actually good**: grounded answers, tracked quality, no guessing
- 🎬 4+ years as a freelance video editor and motion graphics artist for esports organizations
- 🏆 All India Rank 31 at the IIT Bombay E-Summit
- 📣 Learning in public, with weekly updates on what I learned and what broke

## 🧭 Where I'm headed

<p align="center">
  <img src="roadmap.svg" alt="Roadmap: Python, DSA, AI" width="100%"/>
</p>

## 🚀 Projects

### 🔎 Production-Grade RAG System with Observability &nbsp;`in progress`

Ask questions over a document corpus and get answers that **cite the exact sources** behind them.

- **Hybrid retrieval:** BM25 keyword search plus Chroma vector search, merged and ranked
- **Quality is measured:** every change is scored with Ragas for faithfulness and answer relevancy
- **Everything is traced:** Langfuse follows each request end to end
- **Deploys are gated:** a GitHub Actions pipeline blocks releases when quality regresses

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma-FF6446?style=flat-square)
![Ragas](https://img.shields.io/badge/Ragas-evaluation-7C3AED?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-tracing-000000?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### 🧘 MindSync: AI-Powered Mental Wellness Platform

Track mood, energy, sleep and journal entries, with an LLM that writes journal reflections, spots patterns and works as a conversational wellness coach. Designed, built and deployed solo.

**[🌐 Live demo](https://mindsync.amritnayak.in)** &nbsp;·&nbsp; **[📂 Source code](https://github.com/amritkn2244/mindsync)**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(Neon)-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![LLM API](https://img.shields.io/badge/LLM_API-D97757?style=flat-square)

### 📰 truNews: AI News Summarizer with Personalized Feeds

An end-to-end pipeline that collects global news, summarizes it with a **local LLM** and serves each user a feed based on their interests, with **$0 in token costs**. Built as a two-person team project.

- **Local inference:** summaries and categories come from an Ollama-hosted model, so nothing depends on paid APIs and user interests stay on the machine
- **Automated ingestion:** an event-driven n8n workflow polls RSS feeds, removes duplicates by hash and sorts stories into Tech, Sports, Business and World
- **Fallback logic:** a regex backup handles cases where the model returns inconsistent formatting
- **Personalized dashboard:** a Next.js 15 app reads each user's saved preferences from Supabase and filters the summaries to match

**[📂 Source code](https://github.com/amritkn2244/truNews_news_summary)**

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-local_LLM-000000?style=flat-square)

### ✂️ Koazy: AI Text Summarizer

Paste long text and get a concise summary in seconds, through a clean, responsive web interface.

- **Model:** summarization with Hugging Face Transformers (`facebook/bart-large-cnn`)
- **Fast API layer:** a FastAPI backend serves the model to a React and Tailwind frontend
- **Deployed:** frontend on Netlify, backend on Render

**[📂 Source code](https://github.com/amritkn2244/koazy_summarizer)**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

### 🤖 Mod Bot: Discord Moderation Bot with ChatGPT

A Discord bot that handles moderation (kick, ban, mute and more) and doubles as a chat assistant: anyone can talk to it by mentioning it or replying to its messages.

**[📂 Source code](https://github.com/amritkn2244/mod_discord_bot)**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Discord](https://img.shields.io/badge/Discord_Bot-5865F2?style=flat-square&logo=discord&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)

## 🛠 Tech stack

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" alt="Next.js" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" alt="GitHub" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" alt="GitHub Actions" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="VS Code" width="42" height="42"/>&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/blender/blender-original.svg" alt="Blender" width="42" height="42"/>
</p>

| Area | What I use |
|---|---|
| **AI / LLMs** | LLM APIs, LangChain, RAG, Hybrid Search (BM25 + vector), Chroma, Ollama (local LLMs), Hugging Face Transformers |
| **LLMOps** | Ragas (evaluation), Langfuse (tracing), GitHub Actions (CI/CD) |
| **Backend & Web** | Python, FastAPI, PostgreSQL, Supabase, React, Next.js, TypeScript, Tailwind CSS, JavaScript, HTML/CSS |
| **Automation** | n8n workflows, Discord bots |
| **Deploy** | Vercel, Render, Netlify, Neon |
| **Creative** | After Effects, DaVinci Resolve, Blender (3D) |

## 🤝 Beyond code

I'm the **Production Team Lead at my college's E-Cell**, running content from concept to delivery for college-wide events. Years of client work taught me to take feedback well and meet deadlines, and I bring the same ownership to every project.

## 💬 Let's talk

I'm open to AI/ML internships and always happy to hear advice from people already working in the field. Reach me on [LinkedIn](https://linkedin.com/in/amritkn2244) or at amritkn2244@gmail.com.

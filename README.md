<p align="center">
  <a href="https://github.com/Yus3n10">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E293B,100:22D3EE&height=220&section=header&text=Ptheusen%20Geagoni&fontColor=F8FAFC&fontSize=56&fontAlignY=38&animation=fadeIn&desc=Software%20Engineer%20building%20practical%20AI%20products&descAlignY=58&descSize=20" alt="Ptheusen Geagoni" width="100%" />
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=21&pause=1200&color=22D3EE&center=true&vCenter=true&width=800&height=35&lines=Computer+Vision+%C2%B7+Backend+%C2%B7+Data+Analytics;Flutter+%2B+FastAPI%2C+shipped+end-to-end;Fresh+Comp+Eng+grad+%E2%80%94+open+to+work" alt="Typing headlines" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OPEN%20TO%20WORK-Software%20Eng%20%C2%B7%20AI%2FML%20%C2%B7%20Backend%20%C2%B7%20Data-10B981?style=for-the-badge&labelColor=0F172A" alt="Open to work" />
  <img src="https://img.shields.io/badge/📍_Talisay_City,_Negros_Occidental,_PH-1E293B?style=for-the-badge&labelColor=0F172A&color=1E293B" alt="Location" />
  <img src="https://komarev.com/ghpvc/?username=Yus3n10&style=for-the-badge&color=7c3aed&labelColor=0F172A&label=PROFILE+VIEWS" alt="Profile views" />
</p>

<p align="center">
  <a href="#-featured-projects"><b>Projects</b></a> &nbsp;·&nbsp;
  <a href="#%EF%B8%8F-tech-stack"><b>Skills</b></a> &nbsp;·&nbsp;
  <a href="#-experience"><b>Experience</b></a> &nbsp;·&nbsp;
  <a href="#-certifications"><b>Certifications</b></a> &nbsp;·&nbsp;
  <a href="#-github-stats"><b>Stats</b></a> &nbsp;·&nbsp;
  <a href="#-lets-connect"><b>Connect</b></a>
</p>

<br />

## 🚀 About Me

I recently graduated with a **B.S. in Computer Engineering** from the Technological University of the Philippines Visayas. I build AI systems, data tools, automation, and backend services — most of my projects start as a way to learn a new technology and end up as something people actually use.

> **7 shipped projects. 1 defended thesis at >92% real-world accuracy. 14 certifications. All built and owned solo, end to end — from the database schema to what ships in production.**

<table>
<tr>
<td width="33%" valign="top">

### 🧠 AI that ships
Every model I train or wire up sits inside a real workflow — license-plate reads, a chat assistant grounded in your own data, an executive summary of your own numbers. Never a bare demo.

</td>
<td width="33%" valign="top">

### ⚙️ Full stack, solo
Frontend, backend, auth, CI/CD, deploy — I own the whole pipeline on every project, from Flutter release signing to a Raspberry Pi in production.

</td>
<td width="33%" valign="top">

### 🔍 Data-driven
Dashboards, pipelines, and GIS layers that turn raw numbers into something a decision-maker can actually read.

</td>
</tr>
</table>

- 🔭 &nbsp;Currently building **a full-stack platform for my local barangay** — public announcements, an officials-only channel, appointments, and an admin map view.<br>
- 🌱 &nbsp;Currently learning **Spring Boot, Docker, data engineering, and cloud infrastructure.**<br>
- 👯 &nbsp;Looking to collaborate on **civic tech / open-source tools for local government**, and anything that puts computer vision or LLMs to practical use.<br>
- 🤔 &nbsp;Looking for help with **smart-home projects on a Raspberry Pi 5** — voice control works, device control is next.<br>
- 💬 &nbsp;Ask me about **computer vision with YOLO, shipping Flutter + FastAPI end-to-end, or wiring the Gemini API into real products.**<br>
- 😄 &nbsp;Pronouns: **he/him**<br>
- ⚡ &nbsp;Fun fact: a customer once swore their phone **"just randomly died."** I opened it up and found a dead ant that had crawled in and shorted two contacts.<br>
- 🎮 &nbsp;Off the clock: sci-fi, deep conversations, and currently ranked **God of Destruction 1** in Tekken 8 with Devil Jin.

---

## 🧩 Featured Projects

<details open>
<summary><b>🤖 &nbsp;Jarvis — a Raspberry Pi butler that talks first</b></summary>
<br>

A voice-driven calendar assistant on a Raspberry Pi 5 that **announces upcoming appointments unprompted** and repeats until acknowledged — because a reactive assistant is useless when the failure mode is forgetting.

- 🎙️ Always-on **"Hey Jarvis"** wake word (openWakeWord) → **faster-whisper** STT → a pure, fully-tested intent parser
- 🗣️ **Piper** TTS voice output, half-duplex echo gating so it doesn't hear itself talk
- 💬 Optional conversational layer via **Gemini** — deterministic commands (acknowledge/snooze) always stay local; an LLM never decides anything that could mean a missed appointment
- ✅ Read-only Google Calendar OAuth, kept that way on purpose for an honest privacy story

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/Piper_TTS-22D3EE?style=flat-square" />
</p>

<a href="https://github.com/Yus3n10/Jarvis"><img src="https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</details>

<details>
<summary><b>💰 &nbsp;Hamili — AI personal finance tracker</b></summary>
<br>

A cross-platform finance app (Android + Web, single Flutter codebase) with a built-in assistant. People track spending, set budgets and savings goals, and ask a Gemini-powered chat about their own money in plain language — every answer grounded in real transactions, never generic advice.

- Full stack shipped solo: **Flutter** frontend, **FastAPI** backend, **PostgreSQL** via SQLAlchemy, **JWT auth**
- **GitHub Actions** pipeline builds, signs the Android release, and deploys to Firebase Hosting + Render

<p>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
</p>

<a href="https://ptheusengeagoni.netlify.app/projects/hamili"><img src="https://img.shields.io/badge/Case_Study-22D3EE?style=for-the-badge&logo=googlechrome&logoColor=black" /></a>
<a href="https://github.com/Yus3n10/Hamili"><img src="https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</details>

<details>
<summary><b>🚓 &nbsp;SAVES AI — automatic license plate recognition (undergrad thesis)</b></summary>
<br>

A YOLOv11 + OCR pipeline that reads license plates from a camera feed, validates them against a database, and keeps a searchable record. Presented to the **Land Transportation Office** for accuracy approval, and successfully defended as our undergraduate thesis with Engr. Al Christian L. Kardinas.

- **>92%** plate-read accuracy (YOLOv11 + OCR) &nbsp;·&nbsp; **100%** database validation accuracy

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/YOLOv11-111827?style=flat-square" />
<img src="https://img.shields.io/badge/Ultralytics-111F68?style=flat-square&logo=ultralytics&logoColor=white" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/Roboflow-6706CE?style=flat-square&logo=roboflow&logoColor=white" />
<img src="https://img.shields.io/badge/OCR-111827?style=flat-square" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
</p>

<a href="https://ptheusengeagoni.netlify.app/projects/saves-ai"><img src="https://img.shields.io/badge/Case_Study-22D3EE?style=for-the-badge&logo=googlechrome&logoColor=black" /></a>
<a href="https://github.com/Yus3n10/SAVES-AI"><img src="https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</details>

<details>
<summary><b>📊 &nbsp;Steam Player Engagement Analytics — data dashboard with AI-generated summaries</b></summary>
<br>

Collects, cleans, and visualizes Steam game data in an interactive dashboard, then has the Gemini API write an executive summary of what the numbers say — instead of leaving a wall of charts for the reader to interpret.

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/Steam_API-000000?style=flat-square&logo=steam&logoColor=white" />
</p>

<a href="https://ptheusengeagoni.netlify.app/projects/steam-analytics"><img src="https://img.shields.io/badge/Case_Study-22D3EE?style=for-the-badge&logo=googlechrome&logoColor=black" /></a>
<a href="https://github.com/Yus3n10/Steam_Analytics"><img src="https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</details>

<details>
<summary><b>🎓 &nbsp;TUPVConnect — campus communication platform</b></summary>
<br>

Centralizes announcements, events, student organizations, campus maps, and resources for TUP Visayas in one place, with role-based access for students, faculty, and administrators.

<p>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
</p>

<a href="https://ptheusengeagoni.netlify.app/projects/tupvconnect"><img src="https://img.shields.io/badge/Case_Study-22D3EE?style=for-the-badge&logo=googlechrome&logoColor=black" /></a>
</details>

<details>
<summary><b>🐾 &nbsp;Pokémon Image Classifier — computer vision from scratch</b></summary>
<br>

A CNN trained with TensorFlow to recognize **1,000+ Pokémon species** from an uploaded image — built to properly learn the CV workflow: dataset assembly, architecture design, and the unglamorous work of figuring out *why* the model confuses two similar-looking species.

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/CNN-111827?style=flat-square" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white" />
</p>

<a href="https://ptheusengeagoni.netlify.app/projects/pokemon-classifier"><img src="https://img.shields.io/badge/Case_Study-22D3EE?style=for-the-badge&logo=googlechrome&logoColor=black" /></a>
</details>

<details>
<summary><b>🥐 &nbsp;Creer — a small-batch home bakery's Instagram presence, rebuilt as a real website</b></summary>
<br>

Rebuilt a home bakery's Lovable prototype into a production React/TypeScript site — a data-driven content layer so the owner can add menu items without touching code, custom crossfade photo galleries built from raw phone photos, and a resilience layer that keeps animations working even inside Instagram's in-app browser, where standard scroll-trigger APIs are known to silently fail.

- Architected the whole stack solo — **Vite + React + TypeScript + Tailwind v4**, shadcn/ui with every default color token remapped to the client's actual brand palette instead of shipping the default theme
- Built a real content pipeline, not hardcoded pages — menu items, prices, and photos live in typed data files; adding a new product/flavor is a data edit, zero code changes
- Diagnosed and engineered around a real production bug: in-app browsers (Instagram/Facebook webviews — this business's actual traffic source) don't reliably fire `IntersectionObserver` or image `load` events. Shipped a timed fallback so content and animations degrade gracefully instead of silently breaking for real users
- Security-audited before shipping: secret scan, CSP + security headers, honeypot + input validation on the contact form, zero client-side keys
- Full responsive QA, verified at multiple breakpoints with no horizontal overflow, plus accessibility basics (focus states, reduced-motion support, ARIA-correct interactive components)

<p>
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square" />
</p>

<a href="https://github.com/Yus3n10/CreerWeb"><img src="https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</details>

<p align="center"><i>Full write-ups, build notes, and photos for every project above live on my <a href="https://ptheusengeagoni.netlify.app"><b>portfolio</b></a>.</i></p>

---

## 🛠️ Tech Stack

**Languages**

<p align="left">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge" />
<img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/Verilog-334155?style=for-the-badge" />
</p>

**Frameworks & Libraries**

<p align="left">
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Electron.js-47848F?style=for-the-badge&logo=electron&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge" />
</p>

**AI & Data**

<p align="left">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/YOLO-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/Google_Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/Generative_AI-7C3AED?style=for-the-badge" />
<img src="https://img.shields.io/badge/Prompt_Engineering-7C3AED?style=for-the-badge" />
<img src="https://img.shields.io/badge/AI_Agents-7C3AED?style=for-the-badge" />
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" />
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/Google_Analytics-E37400?style=for-the-badge&logo=googleanalytics&logoColor=white" />
<img src="https://img.shields.io/badge/Ultralytics-111F68?style=for-the-badge&logo=ultralytics&logoColor=white" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/Roboflow-6706CE?style=for-the-badge&logo=roboflow&logoColor=white" />
<img src="https://img.shields.io/badge/OCR-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/CNN-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/Piper_TTS-22D3EE?style=for-the-badge" />
<img src="https://img.shields.io/badge/openWakeWord-334155?style=for-the-badge" />
<img src="https://img.shields.io/badge/faster--whisper-334155?style=for-the-badge" />
<img src="https://img.shields.io/badge/Steam_API-000000?style=for-the-badge&logo=steam&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge" />
<img src="https://img.shields.io/badge/RAG-7C3AED?style=for-the-badge" />
</p>

**Databases**

<p align="left">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

**Cloud & DevOps**

<p align="left">
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" />
<img src="https://img.shields.io/badge/Firebase_Hosting-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Docker_Desktop-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/CI%2FCD-22D3EE?style=for-the-badge" />
<img src="https://img.shields.io/badge/REST_APIs-22D3EE?style=for-the-badge" />
<img src="https://img.shields.io/badge/JWT_Auth-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
</p>

**Tools**

<p align="left">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
<img src="https://img.shields.io/badge/Code::Blocks-334155?style=for-the-badge" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
<img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" />
<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
</p>

**Engineering & Design**

<p align="left">
<img src="https://img.shields.io/badge/AutoCAD-E51050?style=for-the-badge&logo=autocad&logoColor=white" />
<img src="https://img.shields.io/badge/Siemens_NX-009999?style=for-the-badge&logo=siemens&logoColor=white" />
<img src="https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white" />
<img src="https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white" />
<img src="https://img.shields.io/badge/Proteus-334155?style=for-the-badge" />
<img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=matlab&logoColor=white" />
<img src="https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white" />
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
<img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white" />
<img src="https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white" />
<img src="https://img.shields.io/badge/GIMP-5C5543?style=for-the-badge&logo=gimp&logoColor=white" />
<img src="https://img.shields.io/badge/Miro-050038?style=for-the-badge&logo=miro&logoColor=white" />
<img src="https://img.shields.io/badge/Uizard-334155?style=for-the-badge" />
</p>

**AI Tools & Automation**

<p align="left">
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white" />
<img src="https://img.shields.io/badge/Codex-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
<img src="https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white" />
<img src="https://img.shields.io/badge/Lovable-8B5CF6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Higgsfield-334155?style=for-the-badge" />
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/Google_AI_Studio-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge" />
</p>

---

## 💼 Experience

<table>
<tr><th align="left">Role</th><th align="left">Organization</th><th align="left">Highlights</th></tr>
<tr>
<td valign="top"><b>Information Systems Intern</b></td>
<td valign="top">Land Transportation Office</td>
<td valign="top">Built a Python + Electron.js MIS that automated monthly revenue recording, replacing a manual process. Ran the technical side of daily operations — displays, files, seminar decks.</td>
</tr>
<tr>
<td valign="top"><b>Computer Hardware Technician Intern</b></td>
<td valign="top">MF Computer Solutions</td>
<td valign="top">Assembled and repaired desktop builds, diagnosed hardware/software issues, tracked inventory across branches, helped customers pick parts.</td>
</tr>
<tr>
<td valign="top"><b>Assistant City Planner Intern</b></td>
<td valign="top">City Government of Talisay</td>
<td valign="top">Prepared and organized GIS datasets for city and landmark mapping projects — working across parcels, zoning, topography, land cover, imagery, and basemap layers.</td>
</tr>
</table>

---

## 📜 Certifications

<p align="left">
<img src="https://img.shields.io/badge/AWS-Cloud_Practitioner_Essentials-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Google-IT_Support_Professional-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/Google-Data_Analytics_Professional-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/Google-AI_Professional-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/SAS-Foundations_of_Cloud_Analytics-1E90FF?style=for-the-badge" />
<img src="https://img.shields.io/badge/Cisco-Hardware_Support_%26_Upgrade-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" />
<img src="https://img.shields.io/badge/Cisco-Digital_Safety_%26_Security-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" />
<img src="https://img.shields.io/badge/Microsoft-Power_BI_Data_Analyst-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/IBM_%C2%B7_Coursera-Project_Manager_Professional-052FAD?style=for-the-badge&logo=ibm&logoColor=white" />
<img src="https://img.shields.io/badge/TechAcademy-Agentic_AI_Masterclass-7C3AED?style=for-the-badge" />
<img src="https://img.shields.io/badge/IBM_%C2%B7_Coursera-RAG_and_Agentic_AI_Professional-052FAD?style=for-the-badge&logo=ibm&logoColor=white" />
<img src="https://img.shields.io/badge/Google-UX_Design_Professional-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/Google-Generative_AI_for_UI%2FUX_Design-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/IBM_%C2%B7_Coursera-Full_Stack_Dev_(in_progress)-334155?style=for-the-badge&logo=ibm&logoColor=white" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats-five-sigma-99.vercel.app/api?username=Yus3n10&show_icons=true&theme=tokyonight&title_color=22D3EE&icon_color=7C3AED&text_color=F8FAFC&hide_border=true&bg_color=00000000&count_private=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats-five-sigma-99.vercel.app/api/top-langs/?username=Yus3n10&layout=compact&theme=tokyonight&title_color=22D3EE&icon_color=7C3AED&text_color=F8FAFC&hide_border=true&bg_color=00000000&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Yus3n10&theme=tokyonight&hide_border=true&background=00000000&ring=22D3EE&fire=7C3AED&currStreakLabel=22D3EE&sideLabels=F8FAFC" alt="Streak stats" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Yus3n10&bg_color=00000000&color=22D3EE&line=22D3EE&point=F8FAFC&area=true&hide_border=true" alt="Activity graph" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Yus3n10/Yus3n10/output/github-contribution-grid-snake.svg" alt="Contribution snake" width="100%" />
</p>


## 💭 Dev Quote

<table align="center">
<tr><td align="center">

*"A man who hasn't hit his Claude limit by noon has wasted his morning."*

**— Claudelius Maximus** <sub>(c. 2026)</sub>

</td></tr>
</table>

---

## 🔗 Let's Connect

<p align="left">
  <a href="https://linkedin.com/in/ptheuseng" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://ptheusengeagoni.netlify.app" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Portfolio-22D3EE?style=for-the-badge&logo=googlechrome&logoColor=black" alt="Portfolio" /></a>
  <a href="mailto:pgeagoni@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:22D3EE,50:1E293B,100:0F172A&height=120&section=footer&animation=fadeIn" alt="footer" width="100%" />
</p>

<p align="center"><i>⭐️ From <a href="https://github.com/Yus3n10">Yus3n10</a> — software engineer building practical AI products.</i></p>

<p align="center"> <a href="https://github.com/Yus3n10"> <img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=22D3EE&fontSize=52&height=90&width=858&text=Hi%2C%20I'm%20Ptheusen%20Geagoni" alt="Hi, I'm Ptheusen Geagoni" /> </a> </p> <p align="center"> <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&pause=1200&color=22D3EE&center=true&vCenter=true&width=900&height=40&lines=Software+Engineer+building+practical+AI+products;Computer+Vision+%C2%B7+Backend+%C2%B7+Data+Analytics;Fresh+Comp+Eng+grad+%E2%80%94+open+to+work" alt="Typing headlines" /> </p> <p align="center"> <img src="https://img.shields.io/badge/OPEN%20TO%20WORK-Software%20Eng%20%C2%B7%20AI%2FML%20%C2%B7%20Backend%20%C2%B7%20Data-10B981?style=for-the-badge&labelColor=0F172A" alt="Open to work" /> <img src="https://img.shields.io/badge/📍-Talisay%20City,%20Negros%20Occidental,%20PH-1E293B?style=for-the-badge&labelColor=0F172A" alt="Location" /> </p> <p align="center"> <a href="#-featured-projects">Projects</a> · <a href="#-tech-stack">Skills</a> · <a href="#-experience">Experience</a> · <a href="#-certifications">Certifications</a> · <a href="#-github-stats">Stats</a> · <a href="#-lets-connect">Connect</a> </p>
About Me
I recently graduated with a Bachelor's degree in Computer Engineering from the Technological University of the Philippines Visayas. I like building software that solves real problems — mostly AI systems, data tools, automation, and backend services. Most of my projects start as a way to learn a new technology and end up as something people can actually use. My own rule for a project: it should be "here's an AI that solves a problem," not "look what algorithm I made."

🔭  Currently building a full-stack platform for my local barangay — public announcements, an officials-only channel, appointments, and an admin map view. 🌱  Currently learning Spring Boot, Docker, data engineering, and cloud infrastructure. 👯  Looking to collaborate on civic tech / open-source tools for local government, and anything that puts computer vision or LLMs to practical use. 🤔  Looking for help with smart-home projects on a Raspberry Pi 5 (currently voice-controlled, working toward device control). 💬  Ask me about computer vision with YOLO, shipping Flutter + FastAPI apps end-to-end, or wiring the Gemini API into real products. 😄  Pronouns: he/him ⚡  Fun fact: a customer once swore their phone "just randomly died." I opened it up and found a dead ant that had crawled in and shorted two contacts. 🎮  Off the clock: sci-fi, deep conversations, and currently grinding Tekken 8 ranked with Devil Jin.

🧩 Featured Projects
<details open> <summary><b>🤖 Jarvis</b> — a Raspberry Pi butler that talks first</summary> <br>
A voice-driven calendar assistant on a Raspberry Pi 5 that announces upcoming appointments unprompted and repeats until acknowledged — because a reactive assistant is useless when the failure mode is forgetting. Wake-word detection, local speech-to-text, and a local-first hybrid that only calls out to Gemini for open-ended chat, never for anything that changes state.

🎙️ Always-on "Hey Jarvis" wake word (openWakeWord) → faster-whisper STT → a pure, fully-tested intent parser
🗣️ Piper TTS voice output, half-duplex echo gating so it doesn't hear itself talk
💬 Optional conversational layer via the Gemini API — deterministic commands (acknowledge/snooze) always stay local; an LLM never gets to decide something that could mean a missed appointment
✅ Read-only Google Calendar OAuth (published, non-expiring) to keep the privacy story honest
Python Raspberry Pi Google Calendar API Gemini API openWakeWord faster-whisper Piper TTS

<a href="https://github.com/Yus3n10/Jarvis"><img src="https://img.shields.io/badge/Repo-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</details> <details> <summary><b>💰 Hamili</b> — AI personal finance tracker</summary> <br>
A cross-platform finance app (Android + Web, single Flutter codebase) with a built-in assistant. People track spending, set budgets and savings goals, and ask a Gemini-powered chat assistant about their own money in plain language — every answer is grounded in their actual transactions, not generic advice.

Full stack shipped solo: Flutter frontend, FastAPI backend, PostgreSQL via SQLAlchemy, JWT auth
GitHub Actions pipeline builds, signs the Android release, and deploys to Firebase Hosting (web) + Render (API)
Flutter Dart FastAPI PostgreSQL SQLAlchemy Google Gemini API Riverpod GitHub Actions

<a href="https://ptheusengeagoni.netlify.app/projects/hamili"><img src="https://img.shields.io/badge/Case%20study-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>

</details> <details> <summary><b>🚓 SAVES AI</b> — automatic license plate recognition (undergrad thesis)</summary> <br>
A YOLOv11 + OCR pipeline that reads license plates from a camera feed, validates them against a database, and keeps a searchable record — built to replace a gate logbook with something automatic. Presented to the Land Transportation Office for accuracy approval, and successfully defended as our undergraduate thesis.

>92% plate-read accuracy (YOLOv11 + OCR) · 100% database validation accuracy
Co-authored with Engr. Al Christian L. Kardinas, TUP Visayas
Python YOLOv11 OCR MySQL

<a href="https://ptheusengeagoni.netlify.app/projects/saves-ai"><img src="https://img.shields.io/badge/Case%20study-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>

</details> <details> <summary><b>📊 Steam Player Engagement Analytics</b> — data dashboard with AI-generated summaries</summary> <br>
Collects, cleans, and visualizes Steam game data in an interactive dashboard — then has the Gemini API write an executive summary of what the numbers actually say, instead of leaving a wall of charts for the reader to interpret.

Python Pandas NumPy MySQL Streamlit Plotly Google Gemini API

<a href="https://ptheusengeagoni.netlify.app/projects/steam-analytics"><img src="https://img.shields.io/badge/Case%20study-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>

</details> <details> <summary><b>🎓 TUPVConnect</b> — campus communication platform</summary> <br>
Centralizes announcements, events, student organizations, campus maps, and resources for TUP Visayas in one place, with role-based access for students, faculty, and administrators.

React Node.js MySQL REST APIs JavaScript

<a href="https://ptheusengeagoni.netlify.app/projects/tupvconnect"><img src="https://img.shields.io/badge/Case%20study-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>

</details> <details> <summary><b>🐾 Pokémon Image Classifier</b> — computer vision from scratch</summary> <br>
A CNN trained with TensorFlow to recognize 1,000+ Pokémon species from an uploaded image. Built to properly learn the CV workflow end-to-end: dataset assembly, architecture design, and the unglamorous work of figuring out why the model confuses two similar-looking species.

Python TensorFlow CNN

<a href="https://ptheusengeagoni.netlify.app/projects/pokemon-classifier"><img src="https://img.shields.io/badge/Case%20study-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>

</details> <p align="center"><i>Full write-ups, build notes, and photos for every project above live on my <a href="https://ptheusengeagoni.netlify.app">portfolio</a>.</i></p>
🛠️ Tech Stack
Languages

<p align="left"> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" /> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" /> <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" /> <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white" /> <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" /> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" /> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" /> <img src="https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white" /> <img src="https://img.shields.io/badge/Verilog-1E293B?style=for-the-badge" /> </p>
Frameworks & Libraries

<p align="left"> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Electron.js-47848F?style=for-the-badge&logo=electron&logoColor=white" /> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" /> </p>
AI & Data

<p align="left"> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" /> <img src="https://img.shields.io/badge/YOLO-111827?style=for-the-badge" /> <img src="https://img.shields.io/badge/Google%20Gemini%20API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" /> <img src="https://img.shields.io/badge/Generative%20AI-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/Prompt%20Engineering-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/AI%20Agents-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" /> <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" /> <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" /> <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" /> <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" /> <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" /> <img src="https://img.shields.io/badge/Google%20Analytics-E37400?style=for-the-badge&logo=googleanalytics&logoColor=white" /> </p>
Databases

<p align="left"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" /> <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" /> </p>
Cloud & DevOps

<p align="left"> <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" /> <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" /> <img src="https://img.shields.io/badge/Firebase%20Hosting-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" /> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" /> <img src="https://img.shields.io/badge/CI%2FCD-22D3EE?style=for-the-badge" /> <img src="https://img.shields.io/badge/REST%20APIs-22D3EE?style=for-the-badge" /> <img src="https://img.shields.io/badge/JWT%20Auth-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" /> </p>
Tools

<p align="left"> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /> <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" /> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" /> </p>
💼 Experience
Role	Organization	Highlights
Information Systems Intern	Land Transportation Office	Built a Python + Electron.js MIS that automated monthly revenue recording, replacing a manual process. Ran the technical side of daily operations (displays, files, seminar decks).
Computer Hardware Technician Intern	MF Computer Solutions	Assembled and repaired desktop builds, diagnosed hardware/software issues, tracked inventory across branches, helped customers pick parts.
Assistant City Planner Intern	City Government of Talisay	Prepared and organized GIS datasets for city and landmark mapping projects.
📜 Certifications
<p align="left"> <img src="https://img.shields.io/badge/AWS-Cloud%20Practitioner%20Essentials-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" /> <img src="https://img.shields.io/badge/Google-IT%20Support%20Professional-4285F4?style=for-the-badge&logo=google&logoColor=white" /> <img src="https://img.shields.io/badge/Google-Data%20Analytics%20Professional-4285F4?style=for-the-badge&logo=google&logoColor=white" /> <img src="https://img.shields.io/badge/Google-AI%20Professional-4285F4?style=for-the-badge&logo=google&logoColor=white" /> <img src="https://img.shields.io/badge/SAS-Foundations%20of%20Cloud%20Analytics-1E90FF?style=for-the-badge" /> <img src="https://img.shields.io/badge/Cisco-Hardware%20Support%20%26%20Upgrade-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" /> <img src="https://img.shields.io/badge/Cisco-Digital%20Safety%20%26%20Security-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" /> <img src="https://img.shields.io/badge/Microsoft-Power%20BI%20Data%20Analyst-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" /> <img src="https://img.shields.io/badge/IBM%20%C2%B7%20Coursera-Project%20Manager%20Professional-052FAD?style=for-the-badge&logo=ibm&logoColor=white" /> <img src="https://img.shields.io/badge/TechAcademy-Agentic%20AI%20Masterclass-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/IBM%20%C2%B7%20Coursera-Full%20Stack%20Dev%20(in%20progress)-334155?style=for-the-badge&logo=ibm&logoColor=white" /> </p>
📊 GitHub Stats
<p align="center"> <img height="165" src="https://github-readme-stats-five-sigma-99.vercel.app/api?username=Yus3n10&show_icons=true&theme=tokyonight&title_color=22D3EE&icon_color=7C3AED&text_color=F8FAFC&hide_border=true&bg_color=00000000&count_private=true" alt="stats" /> <img height="165" src="https://github-readme-stats-five-sigma-99.vercel.app/api/top-langs/?username=Yus3n10&layout=compact&theme=tokyonight&title_color=22D3EE&icon_color=7C3AED&text_color=F8FAFC&hide_border=true&bg_color=00000000&langs_count=8" alt="top langs" /> </p> <p align="center"> <img src="https://github-profile-trophy.vercel.app/?username=Yus3n10&theme=nightowl&no-frame=true&no-bg=true&margin-w=8&row=1" alt="trophies" /> </p> <p align="center"> <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Yus3n10&bg_color=00000000&color=22D3EE&line=22D3EE&point=F8FAFC&area=true&hide_border=true" alt="activity graph" /> </p> <p align="center"> <img src="https://raw.githubusercontent.com/Yus3n10/Yus3n10/output/github-contribution-grid-snake.svg" alt="contribution snake" width="100%" /> </p> <p align="center"><i>Snake animation needs a workflow enabled once in this repo — see <code>.github/workflows/snake.yml</code> included alongside this file.</i></p>
💭 Dev Quote
<p align="center"> <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=discord_dark" alt="Dev quote" /> </p>
🔗 Let's Connect
<p align="left"> <a href="https://linkedin.com/in/ptheuseng" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a> <a href="https://ptheusengeagoni.netlify.app" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Portfolio-22D3EE?style=for-the-badge&logo=googlechrome&logoColor=black" alt="Portfolio" /></a> <a href="mailto:pgeagoni@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a> </p> <p align="center"><i>⭐️ From <a href="https://github.com/Yus3n10">Yus3n10</a> — software engineer building practical AI products.</i></p>

# <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"> Hi, I'm Yash Jain

### Cyber Security Student • Flutter Developer • Full Stack Developer • Embedded & Systems Builder • Researcher

> Building secure, offline-first software that solves real-world problems.

<p align="left">
  <a href="mailto:yashjain5108@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail">
  </a>
  <a href="https://www.linkedin.com/in/yash-jain-540a9a271/">
    <img src="https://img.shields.io/badge/LinkedIn-Yash%20Jain-blue?style=for-the-badge&logo=linkedin">
  </a>
  <a href="https://github.com/Yash5108">
    <img src="https://img.shields.io/badge/GitHub-Yash5108-black?style=for-the-badge&logo=github">
  </a>
</p>

---

# 👨‍💻 About Me

🎓 B.Tech Computer Science & Engineering (Cyber Security), Jain University, Bengaluru  
📍 From Kolhapur, Maharashtra • studying in Bengaluru, Karnataka

I'm passionate about **Cyber Security**, **resilient and offline-first systems**, **Flutter development**, and **building software that people actually use.** My work spans secure full-stack applications, ESP32 mesh networking, robotics orchestration, Android forensics and applied research.

Highlights:

- 🛡 Technical Lead — Cyber Security Club (Salus), Jain University
- 📑 2 patent applications (SYNCHIVE offline-first NAS, explainable business-data visualization) + 1 invention disclosure under review (AgriTrust)
- 📄 1 published paper (IRJMETS), 2 papers under review (ShadowLoc GNSS spoofing, multimedia encryption) and a post-quantum TLS paper being revised
- 🏆 4 hackathon podium finishes, including 1st at Rezonix Researchthon 2025
- 🎓 Cisco Ethical Hacker (Cisco Networking Academy)
- 🚀 Built a production Flutter application used daily by a real business
- 💡 Love solving real engineering problems with secure architectures

---

# 🚀 Featured Projects

## 🛍️ Yash Creations
Production offline Flutter application used by a wholesale jewellery manufacturer. Solely owned: architecture, features, deployment and maintenance.

**Tech**

`Flutter` `Riverpod` `Drift` `SQLite` `go_router` `GitHub Actions`

### Features

- 📦 Inventory & raw-material management
- 🧮 BOM costing with count/weight units
- 🧾 GST invoicing and PDF bills
- 💰 Party ledgers, statements with running balance, party-specific pricing
- 📊 Activity logs, dashboard, global search, date filters
- 🔄 Zip-based backup & restore
- ⚙ CI/CD with signed APK releases
- 🧱 Database schema at v11; a prior version is in daily use on a customer's tablet

---

## 🤖 REO — Resilient Edge Orchestrator *(SIH26123)*

Warehouse autonomous-robot fleet orchestration that keeps working when central connectivity is lost. Team of three; preparing the live demo for the Smart India Hackathon selection round.

**Tech**

`ROS 2 Jazzy` `Open-RMF` `Python` `Ubuntu 24.04` `Azure`

### Features

- 🗺 Central coordination when connected
- 🔁 Peer-to-peer fallback when disconnected
- 👑 Leader election
- 💓 Liveliness monitoring
- ♻ Automatic failover

---

## 🔎 Android Rapid Evidence Triage & Forensic Preview Tool

On-scene Android forensic triage built with a hackathon team.

**Tech**

`Python` `FastAPI` `ADB` `SQLite`

### Features

- 🔌 Read-only ADB acquisition with integrity preservation
- 🗃 Deleted-data recovery from SQLite WAL and rollback journals
- 💬 WhatsApp message recovery
- ✅ Validated against FQLite v4.22

---

## 🌾 AgriTrust Score *(Team Error404)*

A calibration engine that corrects Sentinel-2 mixed-pixel errors on sub-hectare Indian smallholder plots to support agricultural credit scoring. Built for the VIT Chennai hackathon (Round 2). Organizers asked the team to switch to a new project (VaniGuard) because of gaps in event management, so AgriTrust was not presented there, but it was built as intended and is covered by an invention disclosure below.

- 🛰 Cross-validation against Sentinel-1 SAR and a transient soil probe
- 📐 Constrained unmixing and ensemble residual correction
- 🔍 SHAP attribution for explainable scores
- 📟 ESP32 probe wand and reference station

---

## 🎙 VaniGuard *(VIT Chennai Hackathon)*

Real-time audio authentication and voice-spoofing defense system with a mobile client, built on the spot when the event switched the team's project.

**Tech**

`Python` `Flutter` `Android (Kotlin/Gradle)` `GitHub Actions`

### What I built

- ⚡ Optimized audio-transfer latency in the backend processing pipeline
- 🕒 Fixed the audio cooldown timestamp logic
- 📦 GitHub Actions automation that compiles and releases tagged Android APKs (v1.0.4, demo-ready)

---

## 🏴 Salus Event 2 — Binary Exploitation CTF

Collegiate capture-the-flag challenge set on binary exploitation. Authored the challenges, organized the event and ran the deployment infrastructure.

**Tech**

`C` `Linux` `Docker` `GDB` `Python (pwntools)` `Netcat`

### What I built

- 🧩 5 binary exploitation challenges: blockchain_breaker, cybernetic_infection, dimensional_rift, format_hell, neural_nightmare
- 🐳 Containerized, isolated network-accessible deployment of every challenge with Docker
- ✅ Exploit verification scripts, flag delivery infrastructure and beginner-friendly solve write-ups

---

## 🚪 CUSTOS

3-sensor embedded security and access-control system with biometric authentication and video surveillance.

**Tech**

`ESP32` `ESP32-CAM` `C++` `WebSockets` `HTML/CSS/JS`

### Features

- 🖐 Fingerprint verification interface
- 📹 Dedicated ESP32-CAM video streaming module
- 📟 Real-time security dashboard over a unified local network
- 🧱 Refactored firmware for the 3-sensor array

---

## 🧠 NeuroLearn *(ongoing, team of four)*

AI-powered adaptive education platform that detects student focus using biometric signals. A multi-milestone course project (TDPCL): the first review milestone is achieved and the remaining milestones are in progress.

**Tech**

`React` `Node.js` `Express` `Python` `MediaPipe` `XGBoost` `scikit-learn` `SQLite`

### Features

- 👀 Eye, face and gaze tracking (EAR, MAR, blendshapes) in a Web Worker
- 📈 Attention-state classification and abandonment prediction
- 🤖 LLM learning assistant with text scaffolding
- 📊 Live focus meter and analytics dashboard, Focus/Explore modes
- 😴 Fatigue detection with micro-break prompts
- 📚 Milestone 1: balanced ~20,137-record student dataset, EDA, Random Forest vs SVM benchmark, parent/guardian auth and student profile backend

---

## 🔐 Secure Local NAS Server

A secure Python NAS server for LAN environments. [Source](https://github.com/Yash5108/Python-Based-Local-NAS)

### Security Features

- HTTPS/TLS 1.2+
- SHA-256 password hashing
- Rate limiting
- CSRF protection
- Security headers
- Audit logging
- Restricted filesystem access
- SSE live-reload with heartbeat checks and dead-connection culling
- Thread-isolated, non-blocking SSL handshakes (fixed a server freeze during negotiation)
- Streaming multipart upload parser that keeps RAM flat on multi-gigabyte files

---

## 🌐 No-Code Website Builder

Capstone project with drag-and-drop editing, published as a research paper. [Source](https://github.com/SambhavOswal1978/website-builder)

- React
- Secure session handling
- Frontend state persistence

---

## 🛰 More Builds

- 🔎 **Sakshya** — evidence management and forensic-integrity triage platform from the Surat Hackathon; I led the front end (single-page router, hash verification, chain-of-custody and triage panels)
- 🪪 **Hacker House Goa '26 ID Generator** — Next.js + HTML Canvas badge generator for event participants
- 📡 **WiFi-DensePose (RuView)** — ESP32-S3 CSI node firmware: fixed a WPA auth mismatch, a FreeRTOS stack overflow and missing git submodules; working on open-network provisioning
- 🧑‍⚖️ **Exam Supervision Software** — CCTV suspicious-behavior detection with OpenCV, MediaPipe and an SVM (93.9% accuracy)
- 🎓 **Salus Peer Learning Sessions** — front-end redesign of a mentor/student session scheduler (Next.js 14, Tailwind, dark mode, security headers)
- 🧊 **Salus event front-ends** — event front-end systems I designed myself with interactive 3D components
- 📚 **Salus Case File** — interactive flipbook (React, react-pageflip)
- 🌐 **ShunyaNOC** — air-gapped on-prem AI copilot that predicts and prevents network failures (co-creator)
- 🎞 **Li Bai Video-Frame Encryption** — Python frame extraction, encryption and reconstruction (ongoing)
- 💸 **Expense Tracker** — Flutter + sqflite ([Source](https://github.com/Yash5108/Expense-Tracker-App-Flutter))
- 🧾 **Document scanner** — Python + Tesseract OCR
- 🧊 **3D web models** — react-three-fiber prototypes

---

# 🔬 Research

### Published

- **No-Code Website Builder** — *International Research Journal of Modernization in Engineering Technology and Science (IRJMETS)* • [Paper](https://www.irjmets.com/paperdetail.php?paperId=c3c71029304bcffd12af815e664738b8&title=NO+CODE+WEBSITE+BUILDER+&authpr=Prithviraj+Chandrakant+Sutar)

### Under Review (submitted, awaiting results)

- **ShadowLoc: Physics-Anchored Self-Supervised Detection of GNSS Spoofing with Conformal Guarantees on Commodity Smartphones**
  - Co-authors: Harshit S Jain, Aayushi R, Yash Dineshkumar Jain, Sunanda Das (Dept. of CSE (Cybersecurity), Jain University)
  - Self-supervised, real-time GNSS spoofing detector for Android combining physics-based detection, self-supervised learning and conformal prediction
  - Simulation: raises recall on stealthy carry-off attacks from 3% to 52% and keeps the false-alarm rate near the target
  - Keywords: GNSS security, sensor fusion, conformal prediction, on-device ML
- **Multimedia Audio Encryption** *(working title)*
  - Audio encryption paper that grew out of the Rezonix Researchthon 2025 report

### In Progress

- **Does a Slow-Start Staircase Explain Post-Quantum TLS 1.3 Handshake Latency on Constrained Links? An Emulation Study with Migration-Timing Context**
  - Co-authors: Harshit S Jain, Aayushi R, Yash Dineshkumar Jain, Ronak M Surana, Anirudha Prabhu B P (Jain University and PES University)
  - Returned for improvement (Revision 2) before resubmission to Discover Computing (Springer Nature); being revised by the team, not currently under journal review
  - Tests whether a textbook TCP slow-start model can predict how much longer post-quantum TLS 1.3 handshakes (ML-KEM, ML-DSA) take on slow, constrained links
  - Linux network-namespace and netem emulation across 170 parameter cells (RTT, bandwidth, loss, MTU, initial window) with packet captures, over six classical, hybrid and pure post-quantum suites
  - Compares size-only, bandwidth-aware and slow-start latency models
  - Supporting Monte Carlo analysis of Mosca's inequality for harvest-now-decrypt-later risk
  - Framed as a negative result with explicit limitations

---

# 📑 Patents

- **SYNCHIVE — Autonomous Offline-First Microcontroller-Based Network Storage System** *(patent application)*
  - Under-INR-700 ESP32-based hybrid NAS for disconnected and resource-constrained environments • **2nd place, Inceptrix National Hackathon 2026**
  - Self-hosted Wi-Fi access point with a PWA interface, encrypted file sharing, offline real-time chat
  - ESP-NOW mesh synchronization and adaptive chunked uploads for stable large-file transfers
  - Tech: `ESP32` `ESP-NOW` `PWA` `Embedded C/C++` `SD-card storage`
- **Automated Management & Explainable Visualization of Heterogeneous Business Data** *(patent application)*
  - Pipeline that ingests, manages and transforms heterogeneous business data into explainable visual insights
  - Explainability layers that address black-box analytics in enterprise environments
- **A Hardware-Calibrated System and Method for Correcting Mixed-Pixel Spectral Aberration in Sub-Hectare Geospatial Vegetation Indices** *(invention disclosure form submitted, under review)*
  - Portable soil probe captures transient dielectric permittivity and bulk electrical conductivity, mapped to a soil reflectance prior that constrains server-side linear spectral unmixing
  - Cross-validated with Sentinel-1 C-band SAR; outputs unbiased vegetation indices, uncertainty bounds and feature attribution
  - Powers the AgriTrust Score project

---

# 💻 Tech Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

### Frameworks & Libraries

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-6C63FF?style=flat)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite)
![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat&logo=ros&logoColor=white)

### Embedded & Systems

`ESP32` `ESP-NOW` `FreeRTOS` `Arduino` `PlatformIO` `Linux` `TCP/IP` `Bash` `WSL` `Open-RMF`

### ML & Vision

`scikit-learn` `XGBoost` `pandas` `TensorFlow` `OpenCV` `MediaPipe` `SHAP`

### Cyber Security

- OWASP Top 10
- Network Security
- Vulnerability Assessment
- Ethical Hacking
- Digital Forensics
- Threat Analysis
- HTTPS/TLS
- Cryptography
- Post-Quantum Cryptography (ML-KEM, ML-DSA)
- SIEM Basics

### Tools

Git • GitHub • GitHub Actions • Kali Linux • Ubuntu • Wireshark • Nmap • Metasploit • ADB • Android Studio • Azure • Docker • GDB • pwntools

---

# 💼 Experience

### Application Developer
**Yash Creations, Kolhapur**

> Jun 2026 – Present

Solely own a production offline Flutter application: architecture, costing and invoicing features, Drift/SQLite schema, deployment and long-term maintenance, with GitHub Actions CI/CD for signed APK releases.

---

### Full Stack Engineer Intern
**Val-Ed Initiatives, Bengaluru**

> Mar 2026 – May 2026

Built a full-stack Next.js/TypeScript web application across frontend and backend; took part in code audits, UI/UX improvements and feature delivery with multidisciplinary teams.

---

### Technical Lead
**Cyber Security Club (Salus), Jain University**

> Sep 2025 – Present

Lead workshops on cybersecurity, ethical hacking, Generative AI and Agentic AI for 100+ students; run secure code reviews and architectural assessments; author and organize CTF events (Salus Event 2 binary exploitation); design and build the front-end systems for club events, including interactive 3D components.

---

# 🏆 Achievements

🥇 1st Place — Rezonix Researchthon 2025 (IoT & Cybersecurity, two research reports)

🥈 2nd Place — Inceptrix National Hackathon 2026 (600+ Teams)

🥈 Runner-Up — HackVerse 2025 (170+ Teams)

🥉 3rd Place — Cloudathon, Sri Eshwar College of Engineering

🎯 Also: VIT Chennai hackathon (VaniGuard presented, AgriTrust Score built), Hacker House Goa '26, Surat Hackathon, Smart India Hackathon internal round, Odoo Hackathon '26, AI for Management 2026, Innovation Unbound Finale 2026, ETHIndia Villa Builder Sprint

---

# 📜 Certifications

✔ Ethical Hacker — Cisco Networking Academy ([Credential](https://www.credly.com/badges/b7301ff9-7655-4aac-99d2-2a4139d265c3/public_url))

✔ Open Source India 2025

- Command-Line Mastery of Gemini
- Building Agentic Applications with Anthropic

---

# 🎓 Education

- **Jain University, Bengaluru** — B.Tech CSE (Cyber Security), Aug 2025 – Present, CGPA 7.7/10
- **Dr. D. Y. Patil Polytechnic, Kolhapur** — Diploma in Computer Engineering, 2022 – 2025, 85% (A+)

---

# 📈 GitHub Stats

<p align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Yash5108&show_icons=true&theme=tokyonight"/>

<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=Yash5108&theme=tokyonight"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yash5108&layout=compact&theme=tokyonight"/>

</p>

---

# 🌱 Currently Exploring

- Post-Quantum Cryptography and TLS performance
- Digital Forensics
- Resilient edge robotics (ROS 2, Open-RMF)
- ESP32 mesh networking
- AI for Cyber Security
- Secure Flutter Architecture
- Agentic AI
- Malware Analysis
- Reverse Engineering

---

# 🤝 Let's Connect

📧 **Email:** yashjain5108@gmail.com

💼 **LinkedIn:**  
https://www.linkedin.com/in/yash-jain-540a9a271/

💻 **GitHub:**  
https://github.com/Yash5108

---

<p align="center">

### "Build. Break. Secure. Repeat."

</p>

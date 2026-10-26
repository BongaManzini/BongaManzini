# Bonga Manzini 👋
### Software Engineer • AI Systems Developer • Cybersecurity & Informatics Researcher
**Pretoria, South Africa 🇿🇦 • UNISA (BSc Informatics)**

[![Portfolio](https://img.shields.io/badge/🌐_Live_Portfolio-bongamanzini.github.io%2Fportfolio-06b6d4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://bongamanzini.github.io/portfolio/)
[![GitHub Repositories](https://img.shields.io/badge/📦_Public_Repos-42+-10b981?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BongaManzini?tab=repositories)
[![Live Deployments](https://img.shields.io/badge/🚀_Live_Web_Apps-20+-6366f1?style=for-the-badge&logo=vercel&logoColor=white)](https://bongamanzini.github.io/portfolio/)
[![DIRISA 2026 Finalist](https://img.shields.io/badge/🏆_DIRISA_Datathon_2026-Finalist-f59e0b?style=for-the-badge&logo=award&logoColor=white)](https://civicpulse-gauteng-2026.netlify.app/)

---

## ⚡ Executive Summary

I am a Software Engineer, AI Systems Developer, and Security Researcher studying **BSc Informatics at the University of South Africa (UNISA)**. My engineering philosophy operates at the convergence of **Computer Science** (low-latency algorithms, distributed systems, cryptographic security), **Business Information Systems** (economic decision-support, compliance automation, process re-engineering), and **Human Experience** (accessibility, civic transparency, and social impact).

From enterprise Active Directory defense and commercial penetration testing to industrial mineral processing AI and cross-platform Web Audio DSP engines, I architect battle-tested, production-ready systems that solve complex challenges.

> 📍 **Live Interactive Showcase**: Explore all 42 repositories with live deployments, architecture popups, and quick-clone commands at **[bongamanzini.github.io/portfolio](https://bongamanzini.github.io/portfolio/)**.

---

## 🏆 Featured Honors & Recognitions

- **DIRISA Student Datathon 2026 Finalist** — Architected **[CivicPulse](https://github.com/BongaManzini/CivicPulse)**, a geospatial machine learning and deprivation-friction analytics engine forecasting voter turnout dynamics across Gauteng ahead of the 2026 Local Government Elections.
- **Mintek Graduate Hackathon Winner / Finalist** — Engineered the **[Mintek Flotation AI Optimizer](https://github.com/BongaManzini/mintek-flotation-ai-optimizer)**, an industrial AI model predicting silica impurity in iron ore froth flotation and prescribing dynamic reagent dosing.
- **NEMISA Discothon 2025** — Created the **[UbuntuSec Platform](https://github.com/BongaManzini/ubuntu-sec)**, a gamified community cybersecurity awareness system anchored in the African philosophy of Ubuntu.

---

## 🛡️ Enterprise Cybersecurity & Threat Defense

### 1. Hands-On Laboratories & Detection Engineering
- **[Active Directory & Threat Hunting Defense Labs](https://github.com/BongaManzini/cybersecurity-threat-hunting-labs)**:
  - **AD Kerberos Defense**: Production Python script auditing Service Principal Names (SPNs), detecting RC4 cipher downgrade vulnerabilities, and identifying AS-REP roasting vectors (`kerberos_ticket_auditor.py`).
  - **Event ID 4769 Detection Engine**: Real-time SOC log parser detecting automated Kerberoasting attack tools (Rubeus, Impacket) via sliding-window request frequency and `0x17` cipher detection (`spn_roast_detector.py`).
  - **Memory Forensics (Volatility 3)**: Automated memory triage utility analyzing `windows.malfind` and `windows.pslist` outputs to carve injected PE headers and detect parent-child process spoofing (`volatility_memory_analysis.py`).
  - **Statistical Network C2 Beacon Hunting**: Delta-time variance and jitter ratio analyzer detecting automated C2 agents (Cobalt Strike, Sliver) and Shannon entropy DNS exfiltration detector (`pcap_c2_beacon_analyzer.py`, `dns_tunnel_detector.py`).
  - **Cloud IAM & OWASP API Audit**: AWS IAM privilege escalation scanner covering 21 known escalation methods and JWT algorithm confusion (`none` alg, RS256/HS256) auditor.

### 2. Commercial Penetration Testing Reports & Red Team Audits
- **[Enterprise Penetration Test Reports & Red Team Audits](https://github.com/BongaManzini/security-audits-and-pentest-reports)**:
  - **Corporate HQ Commercial Pentest Report**: Comprehensive 15-page assessment report for Apex Global Financial Services (PTES & NIST SP 800-115 aligned) with CVSS v3.1 scoring, Java deserialization RCE, AD CS ESC1 certificate template exploitation to Domain Admin, and cloud SSRF to AWS IMDS.
  - **HackTheBox Enterprise Forest Compromise**: Deep red-team operation writeup covering SQL injection initial foothold, dual-homed network pivoting with Chisel SOCKS5, BloodHound graph ingestion, Kerberoasting, remote DCSync, and Golden Ticket persistence.
  - **Web3 Smart Contract Security Audit**: Assessment of an ERC-4626 DeFi yield vault analyzing cross-function reentrancy and first-depositor share inflation attacks with Foundry PoC tests.

### 3. Incident Response Playbooks & CIS Hardening
- **[Incident Response Playbooks & CIS Hardening](https://github.com/BongaManzini/incident-response-playbooks-cis)**:
  - **NIST SP 800-61 Rev 2 SOPs**: Enterprise Ransomware Containment Playbook, Business Email Compromise (BEC) & M365 session kill workflows, and Supply Chain CI/CD poisoning defense.
  - **Automated CIS Benchmark Level 2 Auditor**: Production Bash script inspecting Linux hosts against CIS Level-2 security controls (`cis_level2_auditor.sh`) and generating structured compliance scorecards (`cis_benchmark_reporter.py`).

### 4. Autonomous Threat Detection & Packet Analysis
- **[DeepSentryAI](https://github.com/BongaManzini/deep-sentry-ai)** — Real-time security console for call centers detecting synthetic voice clones, manipulated video feeds, and network anomalies with sub-second latency. `[Python, OpenCV, Audio DSP, AsyncIO]`
- **[Self-Healing Network System](https://github.com/BongaManzini/self-healing-network)** — Autonomous network threat detection system monitoring live packet streams and executing automated iptables/nftables firewall auto-remediation. `[Python, Flask, Scapy, Iptables]`
- **[Network Threat Monitor (C++ / WinPcap)](https://github.com/BongaManzini/network-threat-monitor-cpp)** — High-speed Windows desktop packet sniffer detecting port scans, MITM attacks, and abnormal bandwidth consumption via native Win32 controls. `[C++, WinPcap, Win32 API]`
- **[UbuntuSec Awareness Platform](https://github.com/BongaManzini/ubuntu-sec)** — Gamified cybersecurity education platform rooted in Ubuntu philosophy. `[HTML5 Canvas, JavaScript, CSS3]` • **[Live Demo](https://bongamanzini.github.io/ubuntu-sec/)**
- **[Cybersecurity Threat Intelligence Dashboard](https://github.com/BongaManzini/cybersecurity-threat-dashboard)** — Threat intelligence dashboard visualizing attack vectors across 40,000+ incident logs. `[Jupyter, Voilà, Pandas, Plotly]`

---

## 🤖 Artificial Intelligence, Machine Learning & Research Benchmarks

- **[AI/ML Research Labs & Benchmarks](https://github.com/BongaManzini/aiml-research-labs-benchmarks)**:
  - **RAG & LLM Evaluation Lab**: Quantitative framework computing the RAG Triad (Context Precision, Context Recall, Faithfulness, Answer Relevance) and flagging LLM hallucinations.
  - **Edge Computer Vision Quantization Lab**: Post-Training Quantization (PTQ) benchmark converting FP32 models to INT8 and FP16 via ONNX Runtime, demonstrating a 3.76x CPU speedup and 4.14x NPU speedup with under 0.35% accuracy loss.
  - **Explainable AI (XAI) & Interpretability**: Shapley value (SHAP) feature attribution engine with actionable counterfactual recourse for credit scoring under POPIA and GDPR Article 22.
  - **Streaming Data Contracts & ETL Pipeline**: Schema contract validation engine isolating corrupted events into a Dead Letter Queue (DLQ).
- **[CivicPulse](https://github.com/BongaManzini/CivicPulse)** — *DIRISA Student Datathon 2026 Finalist*: Geospatial ML pipeline predicting voter turnout and deprivation friction across Gauteng. `[Jupyter, Leaflet, Python, Spatial ML]` • **[Live App](https://civicpulse-gauteng-2026.netlify.app/)**
- **[FocusFlux](https://github.com/BongaManzini/focusflux)** — *Cognitive Wellness Platform*: Full-stack ADHD accessibility ecosystem with 8 sensory mini-games and Google Gemini conversational AI. `[React 19, TypeScript, Gemini AI, Firebase, Tailwind]` • **[Live Demo](https://bongamanzini.github.io/focusflux/)**
- **[Mintek Flotation AI Optimizer](https://github.com/BongaManzini/mintek-flotation-ai-optimizer)** — Industrial mineral processing AI model optimizing reagent dosing and predicting silica impurity in froth flotation. `[Python, scikit-learn, Industrial AI]`
- **[ByteCraft Student Risk Predictor](https://github.com/BongaManzini/bytecraft-student-risk)** — Higher-ed predictive analytics platform using Random Forest classification to forecast student dropout vulnerabilities. `[Python, Flask, scikit-learn, Pandas]`
- **[YouTube Commentary NLP Engine](https://github.com/BongaManzini/youtube-commentary-intel)** — Audience intelligence pipeline clustering viewer feedback into actionable insights using VADER and semantic transformers. `[Python, VADER, NLP]`
- **[ImageSense OCR](https://github.com/BongaManzini/imagesense-ocr)** — Computer vision pipeline converting scanned invoices and receipts into structured Excel workbooks. `[Python, OpenCV, Tesseract OCR]`
- **[Algorithmic Trading & Momentum](https://github.com/BongaManzini/algorithmic-trading-models)** — Quantitative trading algorithms simulating RSI momentum indicators and 50/200-day SMA crossovers. `[Python, Pandas, Backtesting]`

---

## 🌐 Full-Stack Software Engineering, Audio & Distributed Systems

### 1. Cross-Platform Audio & Immersive Applications
- **[CrateFlow – Sample Lineage & DJ Transition Engine](https://github.com/BongaManzini/crateflow-audio-engine)**:
  - Cross-platform music discovery and sample ancestry platform built for crate-diggers and DJs.
  - **Web DSP Studio**: Zero-cloud-cost client-side audio engine (Web Audio API) executing a 4-bar automated DJ transition (high-cut filter sweep, bass swap, sample cue drop) and Camelot Wheel harmonic sorting. `[React 19, Web Audio API, Tailwind]` • **[Live Demo](https://bongamanzini.github.io/crateflow-audio-engine/)**
  - **Native Android Client**: Jetpack Compose and Kotlin low-latency audio implementation (`DspCrossfader.kt`).
- **[TryOn – AR Virtual Try-On & Garment Compositing](https://github.com/BongaManzini/tryon-ar-commerce)**:
  - Cross-platform Flutter application featuring on-device selfie segmentation (Google ML Kit), interactive 2D Matrix4 affine transformation canvas, live ARCore/ARKit garment placement, and Shopify GraphQL integration with affiliate parameter injection. `[Flutter, Dart, ARCore, ML Kit]` • **[Live Demo](https://bongamanzini.github.io/tryon-ar-commerce/)**
- **[Finish The Line – Real-Time Party Trivia Web App](https://github.com/BongaManzini/finish-the-line-trivia)**:
  - Progressive word-by-word clue party game featuring 100+ category quote decks (Anime, Hip-Hop, Movies, Gaming), couch co-op keyboard buzzers, and instant LAN Wi-Fi smartphone controller pairing via room codes. `[React 19, TypeScript, Socket.io, Node.js]` • **[Live Demo](https://bongamanzini.github.io/finish-the-line-trivia/)**
- **[SkyApp – AR Celestial Planetarium](https://github.com/BongaManzini/sky-app)** — Mobile-first 3D celestial star map with live camera augmented reality overlay, sidereal time engine, and offline PWA capability. `[HTML5 Canvas, WebGL, Camera AR, PWA]` • **[Live Demo](https://bongamanzini.github.io/sky-app/)**
- **[June 16 Soweto Memorial Experience](https://github.com/BongaManzini/june16-memorial-site)** — Interactive 3D digital memorial honoring the 1976 Soweto Uprising, blending spatial WebGL scenes, archival timelines, and audio soundscapes. `[Three.js, WebGL, React, D3.js]` • **[Live Demo](https://bongamanzini.github.io/june16-memorial-site/)**

### 2. Distributed Systems & Architecture Blueprints
- **[Distributed Systems Architecture Blueprints](https://github.com/BongaManzini/distributed-architecture-blueprints)**:
  - **Transactional Outbox Pattern**: Production simulation eliminating dual-write vulnerabilities by atomically committing domain aggregates and outbox events in a single ACID transaction, paired with Debezium CDC and Redis idempotent consumer deduplication.
  - **Zero-Trust API Gateway**: RFC 6585 compliant Token Bucket rate limiter with continuous mathematical refill, mTLS proxying, and OAuth 2.1 token introspection.

### 3. Browser Automation & IT Support Extensions (Manifest V3)
Located in `Web-Applications/Automation-and-Extensions/`:
- **[DevDesk Pro](https://github.com/BongaManzini/devdesk-pro)** — Manifest V3 Chrome extension automating service desk workflows: DOM macro click-recording, batch ticket clearance, Telviva account unlockers, and QueueMetrics scraping. `[Chrome MV3, Service Workers, DOM Automation]`
- **[IT Support Tools Hub](https://github.com/BongaManzini/it-support-tools-hub)** — Configurable browser extension providing bulk Excel paste-to-action ticket closing and category filter trees. `[Chrome MV3, JavaScript, Automation]`

---

## 🇿🇦 The South African Informatics Portfolio: Civic Verification & Public Services

| Project | Live Demo | Repository | Description |
| :--- | :--- | :--- | :--- |
| **B-BBEE Scorecard Simulator** | [Live App ↗](https://bongamanzini.github.io/bee-simulator-reality-check/) | [`bee-simulator-reality-check`](https://github.com/BongaManzini/bee-simulator-reality-check) | **Mathematical decision-support system** modeling DTI Codes of Good Practice (Gazette 36928). Proves that 100% white-owned SMEs achieve Level 4 compliance through skills and supplier development without equity alteration. |
| **The Law Auditor** | [Live App ↗](https://bongamanzini.github.io/racelaw-auditor/) | [`racelaw-auditor`](https://github.com/BongaManzini/racelaw-auditor) | **Civic verification engine** auditing viral lists of "145 race laws". Verifies cited statutes against the official *Government Gazette*, isolating Section 9(2) Constitutional redress from repealed Apartheid laws. |
| **Xenophobia Myth-Buster** | [Live App ↗](https://bongamanzini.github.io/xenophobia-myth-buster/) | [`xenophobia-myth-buster`](https://github.com/BongaManzini/xenophobia-myth-buster) | **Interactive demographic visualizer** contrasting public estimates against Stats SA Census 2022 enumeration (2.42M foreign-born residents / 3.9% of population) and OECD job creation data. |
| **Apartheid vs Democracy Dual Timeline** | [Live App ↗](https://bongamanzini.github.io/apartheid-vs-democracy-timeline/) | [`apartheid-vs-democracy-timeline`](https://github.com/BongaManzini/apartheid-vs-democracy-timeline) | **Comparative legal timeline** dissecting the "BEE is reverse Apartheid" fallacy by contrasting criminal penal bans (1948–1990) with voluntary developmental redress incentives (1994–2026). |
| **Trade Truth Dashboard** | [Live App ↗](https://bongamanzini.github.io/trade-truth-dashboard/) | [`trade-truth-dashboard`](https://github.com/BongaManzini/trade-truth-dashboard) | **Macroeconomic telemetry tool** tracking South Africa's $14.2B export surplus with the US (platinum group metals, automotive, citrus), active AGOA duty-free status, and specific PEPFAR health funding. |
| **Public Clinic Smart Queue & USSD Triage** | [Live App ↗](https://bongamanzini.github.io/public-clinic-smart-queue/) | [`public-clinic-smart-queue`](https://github.com/BongaManzini/public-clinic-smart-queue) | **Healthcare process re-engineering** reducing 6+ hour pre-dawn clinic queues to scheduled arrival windows. Includes chronic medication fast-tracking (CCMDD) and a zero-data USSD gateway simulator (`*120*2546#`). |
| **Stokvel Digital Trust Ledger** | [Live App ↗](https://bongamanzini.github.io/stokvel-digital-ledger/) | [`stokvel-digital-ledger`](https://github.com/BongaManzini/stokvel-digital-ledger) | **Communal FinTech platform** digitizing South Africa's R50-billion informal Stokvel economy with immutable transaction logs, rotational payout coordination, and dispute prevention. |
| **GBV Support & Safe Shelter Directory** | [Live App ↗](https://bongamanzini.github.io/gbv-support-directory/) | [`gbv-support-directory`](https://github.com/BongaManzini/gbv-support-directory) | **Privacy-by-design crisis directory** for domestic abuse survivors. Built with a 1-click Quick Exit (ESC key), disguised tab mode, and direct zero-data hotline dialing (`*120*7867#`). |
| **Spaza-Smart Inventory Predictor** | [Live App ↗](https://bongamanzini.github.io/spaza-smart-inventory/) | [`spaza-smart-inventory`](https://github.com/BongaManzini/spaza-smart-inventory) | **Decision-support forecasting engine** for township Spaza shops predicting stockouts based on the 300%–450% demand surge during monthly SASSA grant payment cycles. *(Python + Web)* |
| **Telco Brand Sentiment Sentinel** | [Live App ↗](https://bongamanzini.github.io/telco-sentiment-sentinel/) | [`telco-sentiment-sentinel`](https://github.com/BongaManzini/telco-sentiment-sentinel) | **Real-time NLP outage monitor and "Anger Index"** tracking customer grievances across Twitter/X and HelloPeter for Rain, Telkom, Vodacom, MTN, and Vumatel. *(Python + VADER)* |

---

## 🛠️ Technical Competencies

```
┌───────────────────┬────────────────────────────────────────────────────────────────────────────────────────┐
│ Domain            │ Technologies & Tools                                                                   │
├───────────────────┼────────────────────────────────────────────────────────────────────────────────────────┤
│ Languages         │ Python 3, TypeScript, JavaScript (ESNext), Kotlin, Dart, Go (Golang), C++, SQL, Bash   │
│ Frameworks & Web  │ React 19, Vite, Tailwind CSS, Three.js / WebGL, Web Audio API, Flutter, Jetpack Compose │
│ Cybersecurity     │ Active Directory, Kerberos, Volatility 3, Splunk SPL, Elastic KQL, Sigma, Wireshark   │
│ Cloud & DevSecOps │ AWS IAM, Docker, GitHub Actions, Terraform, Linux CIS Benchmarks, IMDSv2 Hardening     │
│ AI, ML & Data     │ RAG Triad, ONNX Runtime, Quantization (INT8), SHAP XAI, Google Gemini API, scikit-learn│
│ Distributed Sys   │ Transactional Outbox Pattern, Change Data Capture (CDC), Token Bucket Rate Limiting    │
│ Informatics       │ Process Re-engineering, B-BBEE DTI Modeling, USSD Systems, Decision Support Systems    │
└───────────────────┴────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=BongaManzini&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Bonga's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BongaManzini&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />
</p>

---

## 📫 Let's Connect & Collaborate

- **🌐 Live Developer Portfolio**: [https://bongamanzini.github.io/portfolio/](https://bongamanzini.github.io/portfolio/)
- **💼 LinkedIn**: [linkedin.com/in/bonga-manzini](https://www.linkedin.com/in/bonga-manzini)
- **🐙 GitHub**: [@BongaManzini](https://github.com/BongaManzini)
- **📍 Location**: Pretoria, Gauteng, South Africa

---
<p align="center">
  <em>"Informatics sits at the sweet spot between Computer Science (the code), Business (the process), and People (the user experience)."</em>
</p>

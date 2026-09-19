<!-- RYTHMA REDDY LAKKADY — ENGINEERING PROFILE -->

<p align="center">
  <img src="header.svg" width="100%" alt="Rythma Reddy Lakkady — AI Systems & Software Engineering"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=2800&color=F7A9C4&center=true&vCenter=true&width=900&lines=AI+SYSTEMS+%2F+SOFTWARE+ENGINEERING;Building+intelligent+systems+that+survive+the+messy+path."/>
</p>

<p align="center">
  <a href="https://rythmalakkady.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-5A1537?style=flat-square&logo=vercel&logoColor=F7A9C4"/></a>
  <a href="https://www.linkedin.com/in/rythma-lakkady-1725852a2/"><img src="https://img.shields.io/badge/LINKEDIN-5A1537?style=flat-square&logo=linkedin&logoColor=F7A9C4"/></a>
  <a href="https://github.com/RythmaLakkady"><img src="https://img.shields.io/badge/GITHUB-5A1537?style=flat-square&logo=github&logoColor=F7A9C4"/></a>
  <a href="mailto:rythmalakkady@gmail.com"><img src="https://img.shields.io/badge/EMAIL-5A1537?style=flat-square&logo=gmail&logoColor=F7A9C4"/></a>
</p>

---

## 01 / WHO I AM

I'm **Rythma**, a Computer Science undergraduate who builds at the intersection of **AI, backend systems, and full-stack software**.

I don't want to build AI demos that only work on the happy path. I'm interested in the engineering around them — **orchestration, APIs, retrieval, async workflows, evaluation, caching, reliability, and the product experience around the model.**

> **Build it. Break it. Measure it. Make it useful.**

---

## 02 / SELECTED SYSTEMS

| SYSTEM | WHAT IT PROVES |
|:--|:--|
| 🛡️ **ShadowQA** | AI + API engineering + RAG + asynchronous testing |
| ✈️ **vac-ai-tion** | Full-stack product engineering + LLM orchestration |
| 🚦 **Traffic Demand Prediction** | ML engineering + feature engineering + model evaluation |
| 🔐 **AgentDefender** | Multi-agent orchestration + security-focused AI workflows |

### 🛡️ ShadowQA
**AI-Powered API Testing & Debugging Framework**

ShadowQA turns an OpenAPI specification into an AI-assisted testing workflow — generating adversarial cases, executing requests concurrently, and using previous failures as context for debugging.

**Proof**
- **15** generated happy-path, edge-case & adversarial tests in ~**10s**
- Concurrent API execution with `httpx` + `asyncio`
- RAG debugging with **LangChain + ChromaDB**
- AI-assisted diagnostic reports from historical failures
- Structured vulnerability reports stored in SQLite

`Python` `RAG` `Llama 3.3` `LangChain` `ChromaDB` `asyncio`

<a href="https://github.com/RythmaLakkady/ShadowQA"><img src="https://img.shields.io/badge/VIEW_CODE-3D1026?style=flat-square&logo=github&logoColor=F7A9C4"/></a>
<a href="https://shadowapp.streamlit.app/"><img src="https://img.shields.io/badge/LIVE_SYSTEM-8E365B?style=flat-square&logo=streamlit&logoColor=F7A9C4"/></a>

---

### ✈️ vac-ai-tion
**AI Travel Planning Platform with Asynchronous LLM Orchestration**

A full-stack AI application where itinerary generation runs asynchronously instead of blocking the user. The system validates generated plans, streams progress, and caches repeated requests.

**Proof**
- Planner → Critic workflow with up to **3 validation iterations**
- Firebase Cloud Functions for async generation
- Firestore listeners for real-time progress
- SHA-256 caching reducing repeated LLM calls by up to **6×**
- Persistent itinerary editing and trip history

`React` `Vite` `Firebase` `Firestore` `Groq` `Llama 3.3 70B`

<a href="https://github.com/RythmaLakkady/vac-ai-tion"><img src="https://img.shields.io/badge/VIEW_CODE-3D1026?style=flat-square&logo=github&logoColor=F7A9C4"/></a>
<a href="https://vac-ai-tion.vercel.app/"><img src="https://img.shields.io/badge/LIVE_SYSTEM-8E365B?style=flat-square&logo=vercel&logoColor=F7A9C4"/></a>

---

### 🚦 Traffic Demand Prediction
**Machine Learning for Urban Traffic Forecasting**

A spatial + temporal ML pipeline using a stacked ensemble to predict urban traffic demand.

**Proof**
- **R² = 0.96**
- **41,700+** validation samples
- Geohash-based spatial features
- 5-fold target encoding
- LightGBM + XGBoost + CatBoost + Ridge
- Automated inference pipeline

`Python` `Pandas` `NumPy` `LightGBM` `XGBoost` `CatBoost`

<a href="https://github.com/RythmaLakkady/flipkart-gridlock-traffic-prediction"><img src="https://img.shields.io/badge/VIEW_CODE-3D1026?style=flat-square&logo=github&logoColor=F7A9C4"/></a>

---

### 🔐 AgentDefender
**Multi-Agent AI for Smart Contract Security**

A security-focused multi-agent system exploring how AI agents and static analysis can work together on Solidity smart contracts.

**Core stack**
`LangGraph` `Llama` `Slither` `Solidity`

---

## 03 / MY ENGINEERING LANE

**01 — Intelligent systems**  
LLMs · RAG · Agentic AI · multimodal AI · evaluation

**02 — Backend & systems**  
APIs · async processing · orchestration · databases · distributed systems

**03 — Product engineering**  
React · Node.js · Firebase · full-stack applications · real-time UX

**04 — ML engineering**  
Model development · feature engineering · ensembles · computer vision · inference

---

## 04 / THE STACK

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,cpp,javascript,react,nodejs,express,aws,firebase,docker,mongodb,sqlite,git,linux,tensorflow,pytorch&theme=dark" />
</p>

<p align="center">
  <code>LangChain</code> · <code>LangGraph</code> · <code>ChromaDB</code> · <code>Hugging Face</code> · <code>OpenCV</code> · <code>XGBoost</code> · <code>LightGBM</code> · <code>Gemini</code>
</p>

---

## 05 / HOW I BUILD

```
PROBLEM
   ↓
SYSTEM DESIGN
   ↓
MODEL / API / DATA LAYER
   ↓
ASYNC + FAILURE PATHS
   ↓
MEASURE
   ↓
SHIP
```

I care about **what happens after the demo**: latency, failure modes, repeatability, observability, cost, and whether someone can actually use the thing.

---

## 06 / CURRENTLY BUILDING

```yaml
now:
  - Agentic AI workflows
  - RAG systems
  - Backend & distributed systems
  - Production-oriented AI applications

deepening:
  - System design
  - Cloud architecture
  - Docker / Kubernetes
  - MLOps / LLMOps
  - AI evaluation & reliability

looking_for:
  - Software Engineering
  - AI / ML Engineering
  - Backend Engineering
```

---

## 07 / MILESTONES

**Flipkart GRiD 8.0**  
Semifinalist — advanced to Round 3 among **165,730+ registered participants**.

**Flipkart Gridlock Hackathon 2.0**  
Built a stacked ML ensemble reaching **R² 0.96** on **41,700+ validation samples**.

---

## 08 / ACTIVITY

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=RythmaLakkady&bg_color=0D0B10&color=F7A9C4&line=B85C7A&point=FAD6E3&area=true&hide_border=true" width="100%"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/RythmaLakkady/RythmaLakkady/output/github-contribution-grid-snake.svg" width="100%" alt="GitHub contribution activity"/>
</p>

---

## 09 / ELSEWHERE

<p align="center">
  <a href="https://rythmalakkady.vercel.app"><b>PORTFOLIO</b></a>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/rythma-lakkady-1725852a2/"><b>LINKEDIN</b></a>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <a href="mailto:rythmalakkady@gmail.com"><b>EMAIL</b></a>
</p>

<p align="center">
  <img src="footer.svg" width="100%" alt=""/>
</p>

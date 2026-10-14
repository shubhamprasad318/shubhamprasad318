<p align="center">
  <img src="assets/banner.svg" alt="Shubham Prasad — Software Engineer, Full Stack & GenAI" width="100%" />
</p>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=F7B32B&center=true&vCenter=true&width=640&lines=Building+LLM+systems+that+ship+to+production;LLM+evaluation+%26+SFT+data+infrastructure;Voice+agents+%7C+Multi-agent+systems+%7C+RAG;700%2B+DSA+problems+in+C%2B%2B" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://drive.google.com/file/d/1XLOIUDDpweHK9ryP_gbrgcc-xOIow4Zg/view"><img src="https://img.shields.io/badge/Resume-PDF-D14836?style=for-the-badge&logo=googledrive&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/shubham-prasad-320495196/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://leetcode.com/u/sprasad6417/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
  <a href="mailto:shubhamprasad3758@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.cloudskillsboost.google/public_profiles/c26b27d1-94e0-4623-a42c-12f90f80dc0c"><img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" /></a>
</p>

<p align="center"><i>Measure it, then ship it.</i></p>

---

## 👋 About me

AI Engineer at **Ethara AI** (Gurugram) building production GenAI systems: LLM evaluation and SFT-data infrastructure for a FAANG client, real-time voice agents, and multi-agent LLM applications. I like owning things end to end — from the Dockerfile to the eval dashboard — and I measure before I claim.

B.E. Computer Science, Nitte Meenakshi Institute of Technology, Bangalore (2021–2025, CGPA 8.85).

---

## 📈 Impact at a glance

| | |
|---|---|
| 🐳 **1,200+** multi-arch Docker images across **16 languages** | LLM evaluation infra aligned with Multi-SWE-bench (NeurIPS 2025) |
| 🧪 **50+** open-source projects (Redis, curl, systemd, Valkey) | Registry-driven eval harness scoring LLM patches deterministically |
| 🖼️ **500K+** image training dataset, solo-built pipeline | Multi-provider T2I/I2I orchestration with retries, QA and cost reporting |
| 👥 **1,600+** users on AWS EKS | Company-operations platform built and deployed single-handedly |
| ⚡ **~2s** voice-agent latency · **60%** lower ops cost | Dual-LLM realtime routing; LLM workflows moved to Lambda |
| 🧠 **700+** DSA problems · 🏆 **1st prize**, iNeuron (PW) Hackathon | C++ for DSA, Python for everything AI |

---

## 💼 Experience

**Ethara AI** — Software Engineer, Full Stack & GenAI · *Feb 2026 – Present*

- Built LLM evaluation infrastructure for a FAANG client: 1,200+ multi-arch Docker images (amd64/arm64) across 16 languages with BuildKit on AWS ECR for high-throughput parallel evaluation.
- Designed a registry-driven evaluation harness with per-repo build/dependency/test configs for 50+ open-source projects, scoring LLM-generated patches in isolated containers.
- Built the end-to-end Python pipeline that produced an SFT dataset for a FAANG model: mined bounty-linked GitHub issues, filtered issue-resolving PRs, extracted verified fix/test patches into JSONL ground truth.
- Solo-built a pipeline that generated a 500K+ image training dataset for a FAANG research team: SOTA model benchmarking, multi-provider APIs with concurrency and rate-limit handling, automated quality checks, live cost reporting.
- Built and deployed Ethara's company-operations platform (Flutter, Odoo, PostgreSQL, EKS) used by 1,600+ people.

**Meta Design Solution** — Software Engineer, Full Stack & GenAI · *May 2025 – Oct 2025*

- Production agentic voice agent for payment-reminder calls (FastAPI, LiveKit, OpenAI Realtime, Gemini Realtime, ElevenLabs, Twilio) with identity verification and risk-based escalation.
- Dual-LLM realtime inference with context-based routing at ~2s latency; migrated LLM workflows to AWS Lambda + API Gateway, cutting operational costs by 60%.

---

## 🚀 Featured projects

### 🩺 [AI HealthEngine](https://github.com/shubhamprasad318/AI_health_care) · [Live demo](https://ai-healthengine.onrender.com)
Health platform with a **voice doctor**. A calibrated LightGBM symptom-checker trained on the DDXPlus benchmark (1.16M patients, 49 conditions). Diagnosed poor accuracy on short inputs and retrained on partial-symptom copies, **raising 3-symptom top-3 accuracy from 57% → 97%**. A LiveKit + Gemini Live voice doctor reads each patient's history (consultations, labs, missed medicines) to follow up across visits, with a rule-based emergency system catching 91% of life-threatening cases from 3 symptoms.

`FastAPI` `LightGBM` `React` `MongoDB` `Gemini` `LiveKit`

### 🌍 [Multi-Agent Travel Orchestrator](https://github.com/shubhamprasad318/multi-agent-travel-orchestrator)
LangGraph pipeline where **6 specialized agents plan in parallel** with live SSE progress; a self-correcting validator scores each plan on 6 weighted criteria and sends low scorers back for revision, with budget arithmetic kept in code. Comes with its own **evaluation harness** (16 fixed trips, deterministic checks, LLM judge, revision-loop ablation) on an `/evals` dashboard, an 8-model quota-aware fallback chain, 100+ pytest tests, CI and Docker deploys.

`Python` `FastAPI` `LangGraph` `Gemini` `Next.js` `TypeScript` `MongoDB`

### 🎙️ [LiveKit Universal Agent](https://github.com/shubhamprasad318/LiveKit-Universal-Agent)
Voice AI agent that handles both browser sessions and phone calls (SIP), with RAG over a Pinecone knowledge base.

`Python` `LiveKit` `Pinecone`

<details>
<summary>More projects</summary>
<br/>

- [**Multi-User Blogging Platform**](https://github.com/shubhamprasad318/Multi-User-Blogging-Platform) — Next.js 15, tRPC, Drizzle ORM, PostgreSQL; markdown editing and category management.
- [**Event Management**](https://github.com/shubhamprasad318/event_management) — Node.js event platform with auth, guest login and real-time updates over WebSockets.
- [**Brain Tumor Detection**](https://github.com/shubhamprasad318/brain-tumor-detection) — CNN-based binary and multi-class classification of brain MRI scans.

</details>

---

## 🛠️ Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,java,typescript,js,fastapi,flask,nodejs,express,react,nextjs,flutter&perline=12" alt="Languages and frameworks" />
  <br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,aws,docker,kubernetes,githubactions,git,linux&perline=12" alt="Data and infrastructure" />
</p>

**GenAI & LLMs:** LLM evaluation & benchmarking · SFT dataset curation · AI agents & multi-agent systems · LangGraph · LangChain · RAG · OpenAI / Gemini Realtime APIs · LiveKit · LightGBM · scikit-learn

---

## 📊 GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=shubhamprasad318&show_icons=true&hide_border=true&count_private=true&hide_rank=true&theme=dark&bg_color=0b1020&title_color=f7b32b&icon_color=f7b32b&text_color=b8c1d9" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shubhamprasad318&layout=compact&hide=jupyter%20notebook,html,css&hide_border=true&theme=dark&bg_color=0b1020&title_color=f7b32b&text_color=b8c1d9" />
</p>

---

## 🧩 Problem solving

<p align="center">
  <a href="https://leetcode.com/u/sprasad6417/">
    <img src="https://leetcard.jacoblin.cool/sprasad6417?theme=dark&font=Source%20Code%20Pro&ext=heatmap" alt="LeetCode stats for sprasad6417" />
  </a>
</p>
<p align="center">
  <a href="https://leetcode.com/u/sprasad6417/">
    <img src="https://leetcode-badge-showcase.vercel.app/api?username=sprasad6417&theme=dark&animated=false" alt="LeetCode badges earned by sprasad6417" />
  </a>
</p>

---

## 📄 Resume

<p align="center">
  <a href="https://drive.google.com/file/d/1XLOIUDDpweHK9ryP_gbrgcc-xOIow4Zg/view">
    <img src="https://lh3.googleusercontent.com/d/1XLOIUDDpweHK9ryP_gbrgcc-xOIow4Zg=w800" width="420" alt="Resume of Shubham Prasad (click to open)" />
  </a>
  <br/>
  <a href="https://drive.google.com/file/d/1XLOIUDDpweHK9ryP_gbrgcc-xOIow4Zg/view"><img src="https://img.shields.io/badge/View%20full%20resume-D14836?style=for-the-badge&logo=googledrive&logoColor=white" /></a>
</p>

---

<p align="center">
  📫 Open to <b>SDE and AI/ML engineering roles</b> · Gurugram, open to relocating to Bengaluru<br/>
  <a href="mailto:shubhamprasad3758@gmail.com">shubhamprasad3758@gmail.com</a> · <a href="https://www.linkedin.com/in/shubham-prasad-320495196/">LinkedIn</a>
</p>

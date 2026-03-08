# 🗺️ Cloud & AI/ML Engineer Roadmap — Interactive Tracker

> A personal, interactive learning roadmap built to track my journey toward becoming a **MLOps & Cloud Infrastructure Engineer**.  
> Live, persistent progress tracking — works on any device via browser.

🔗 **Live Site:** (https://tanmoy-maiti.github.io/MLOps_-_Cloud_Infratructure_roadmap/)
---

## 📸 Preview

> *Phase overview with module cards and progress bars*

```
┌─────────────────────────────────────────────────────────────┐
│  Cloud & AI/ML Engineer          Career Roadmap 2026  [ 0%] │
├──────────┬──────────┬──────────┬──────────┬─────────────────┤
│ Ph.1     │ Ph.2     │ Ph.3     │ Ph.4     │ Ph.5            │
│ 🧱 Found │ ⚙️ Core  │ ☁️ Cloud │ 🤖 AI    │ 🏗️ Portfolio   │
├──────────┴──────────┴──────────┴──────────┴─────────────────┤
│  SIDEBAR          │  MODULE CARDS / CONCEPT DETAIL           │
│  ─────────────    │  ────────────────────────────────────    │
│  ▸ DSA            │  ┌──────────────┐  ┌──────────────┐     │
│  ▸ OS             │  │ DSA — Light  │  │ Operating    │     │
│  ▸ Networking     │  │ 7 concepts   │  │ Systems      │     │
│  ▸ Linux & Bash   │  │ ░░░░░░ 0%    │  │ 6 concepts   │     │
│  ▸ Python         │  └──────────────┘  └──────────────┘     │
│  ▸ SQL            │                                          │
│  ...              │                                          │
└───────────────────┴──────────────────────────────────────────┘
```

---

## ✨ Features

### 🔖 5 Structured Phases
The roadmap is split into 5 phases covering the full journey from CS fundamentals to production AI systems:

| Phase | Title | Timeline | Focus |
|-------|-------|----------|-------|
| 1 | 🧱 Foundations | Months 1–2 | DSA, OS, Networking, Linux, Python, SQL, Math |
| 2 | ⚙️ Core ML & Deep Learning | Months 2–4 | PyTorch, CNNs, Transformers, ML Pipelines |
| 3 | ☁️ Cloud + MLOps | Months 4–6 | Docker, Kubernetes, AWS, CI/CD, Certifications |
| 4 | 🤖 Modern AI Stack | Months 6–9 | LLMs, RAG Systems, Agents, LangChain, Prompt Engineering |
| 5 | 🏗️ Portfolio & Career | Months 9–12 | Projects, System Design, Interviews, Career Strategy |

---

### 📦 Module Cards
Each phase contains multiple **learning modules**. On the main view, every module appears as a card showing:
- Module title and depth level (`Deep` / `Core` / `Practical`)
- Total number of concepts inside
- A preview of the first 3 concept names with completion status
- A live progress bar showing how many concepts are done

Click any card to open the full concept list for that module.

---

### ✅ Concept Checklist
Inside each module, every concept has:
- A **name** — the specific topic to learn
- A **detail line** — exactly what to study, which tools to use, and why it matters for the job
- A **circular checkbox** — click to mark as learned; it fills with the phase color

Example concept inside *Linux & Bash Mastery*:
```
○  SSH & Remote Work
   ssh keys, scp, rsync, tmux/screen, port forwarding —
   working with remote GPU servers and cloud VMs daily
```
Click it → it turns green with a ✓ and is saved instantly.

---

### 💾 Persistent Progress (localStorage)
Your progress is **automatically saved to your browser's localStorage** every time you check or uncheck a concept. This means:
- ✅ Close the tab → reopen → everything is exactly where you left it
- ✅ Works completely offline — no server, no login, no account needed
- ✅ Last active phase tab is also remembered and restored on reopen
- ⚠️ Progress is per-browser — Chrome and Firefox on the same machine have separate storage

A small **✓ Saved** flash appears in the top-right corner each time progress is written to storage.

---

### 📊 Live Progress Tracking
Progress is calculated and displayed at 3 levels simultaneously:

| Level | Where it appears | What it tracks |
|-------|-----------------|----------------|
| **Overall** | Top-right ring + percentage | All concepts across all 5 phases |
| **Per Phase** | Badge on each phase tab | All concepts within that phase |
| **Per Module** | Progress bar on sidebar + card | Concepts within that one module |

All progress bars update in real time as you check concepts off — no page refresh needed.

---

### 🏷️ Depth Labels
Every module is tagged with a depth level so you know how deeply to study it:

| Label | Color | Meaning |
|-------|-------|---------|
| `Deep` | 🔴 Red | Master it — interviews and daily work will test this heavily |
| `Core` | 🔵 Blue | Solid understanding required — foundational knowledge |
| `Practical` | 🟠 Orange | Build with it — focus on hands-on application over theory |

---

### 🔄 Reset Button
A **RESET** button in the top-right header clears all progress after a confirmation prompt. Useful if you want to restart tracking from scratch.

---

## 🗂️ Roadmap Content — Full Module List

<details>
<summary><strong>🧱 Phase 1 — Foundations (click to expand)</strong></summary>

- **DSA — Light & Targeted** `Core` — Arrays, HashMaps, Graphs, Sorting, Light DP
- **Operating Systems** `Core` — Processes, Memory, File Systems, Signals, Concurrency
- **Networking Fundamentals** `Core` — OSI Model, TCP/IP, DNS, Load Balancers, VPC
- **Linux & Bash Mastery** `Deep` — Navigation, Permissions, Shell Scripting, SSH, systemd
- **Python: Production-Grade** `Deep` — OOP, Async, Testing, Clean Architecture, Profiling
- **SQL & Data Engineering** `Deep` — Advanced SQL, Pipelines, Distributed Storage, NoSQL
- **Linear Algebra** `Core` — Vectors, Matrices, Eigendecomposition, Tensors
- **Probability & Statistics** `Core` — Distributions, Hypothesis Testing, Information Theory
- **Calculus for ML** `Core` — Derivatives, Gradient Descent, Computational Graphs

</details>

<details>
<summary><strong>⚙️ Phase 2 — Core ML & Deep Learning (click to expand)</strong></summary>

- **Classical ML Mastery** `Deep` — Supervised/Unsupervised Learning, Evaluation, Feature Engineering
- **PyTorch Deep Dive** `Deep` — Tensors, nn.Module, Training Loops, Optimization, Debugging
- **Neural Network Architectures** `Deep` — CNNs, RNNs, Transformers, ViTs, Generative Models
- **End-to-End ML Pipelines** `Practical` — DVC, MLflow, ONNX, Kaggle Strategy

</details>

<details>
<summary><strong>☁️ Phase 3 — Cloud + MLOps (click to expand)</strong></summary>

- **Docker & Containerization** `Deep` — Dockerfile, Networking, Security, GPU Containers
- **Kubernetes for ML** `Core` — Pods, Deployments, Scaling, Helm Charts
- **AWS for ML Engineers** `Deep` — EC2, S3, SageMaker, Glue, Kinesis, Serverless
- **CI/CD for ML (MLOps)** `Deep` — Pipelines, Model Testing, Drift Monitoring, Feature Stores
- **Cloud Certifications** `Practical` — AWS Cloud Practitioner, AWS ML Specialty, GCP Professional ML

</details>

<details>
<summary><strong>🤖 Phase 4 — Modern AI Stack (click to expand)</strong></summary>

- **LLMs: Deep Understanding** `Deep` — Architecture, Fine-tuning (LoRA/QLoRA), Inference Optimization
- **RAG Systems (Production)** `Deep` — Chunking, Embeddings, Vector DBs, Retrieval, Evaluation
- **Agentic AI Systems** `Deep` — ReAct, LangChain, LangGraph, AutoGen, Memory Systems
- **LLM APIs & Prompt Engineering** `Core` — OpenAI/Anthropic APIs, CoT, Cost Optimization

</details>

<details>
<summary><strong>🏗️ Phase 5 — Portfolio & Career (click to expand)</strong></summary>

- **Portfolio Projects (Tier 1)** `Practical` — Cloud ML API, RAG Chatbot, AI Agent
- **Engineering Best Practices** `Deep` — System Design, FastAPI, Observability, Security
- **Interview Preparation** `Practical` — ML System Design, Coding, Theory, Behavioral
- **Career Strategy** `Practical` — GitHub, LinkedIn, Target Companies, Open Source

</details>

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| UI Framework | React 18 (via CDN — no build step) |
| Language | JSX compiled by Babel Standalone |
| Styling | Inline styles (zero dependencies) |
| Persistence | Browser `localStorage` |
| Hosting | GitHub Pages |

No `npm install`. No `node_modules`. No build pipeline.  
Just one `index.html` file — open it anywhere and it works.

---

## 🚀 Run Locally

```bash
# Clone the repo
git clone [https://github.com/TANMOY-MAITI/roadmap.git](https://tanmoy-maiti.github.io/MLOps_-_Cloud_Infratructure_roadmap/)

# Open directly in browser — no server needed
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or just visit the live site → [tanmoy-maiti.github.io/roadmap](https://tanmoy-maiti.github.io/roadmap)

---

## 👤 About

Built by **Tanmoy Maiti** — B.Tech CSE (AI/ML), 3rd Year, Kolkata.  
Tracking my structured path toward MLOps & Cloud Infrastructure Engineering.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tanmoy_Maiti-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/tanmoy-maiti-161053301/)
[![GitHub](https://img.shields.io/badge/GitHub-TANMOY--MAITI-181717?style=flat&logo=github)](https://github.com/TANMOY-MAITI)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).  
Feel free to fork it, adapt the roadmap content for your own learning path, and deploy your own version.


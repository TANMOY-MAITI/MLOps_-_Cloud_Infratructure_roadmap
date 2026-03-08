# 🗺️ Cloud & AI/ML Engineer Roadmap — Interactive Tracker

> A personal, interactive learning roadmap built to track my journey toward becoming a **MLOps & Cloud Infrastructure Engineer**.
> Fully responsive — works on mobile, tablet, and desktop. Zero dependencies. No install needed.

🔗 **Live Site:** [tanmoy-maiti.github.io/roadmap](https://tanmoy-maiti.github.io/roadmap)

[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222?style=flat&logo=github)](https://tanmoy-maiti.github.io/roadmap)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-00FFB2?style=flat)](#)
[![Mobile Ready](https://img.shields.io/badge/Mobile-Ready-4D9FFF?style=flat)](#)

---

## 📸 Layout Preview

**Desktop** — persistent sidebar + card grid:
```
┌─────────────────────────────────────────────────────────────────┐
│  ☰  Cloud & AI/ML Engineer          OVERALL  23%  [◉]   RESET  │
├──────────┬──────────┬──────────┬──────────┬─────────────────────┤
│ 🧱 P1 0% │ ⚙️ P2 0% │ ☁️ P3 0% │ 🤖 P4 0% │ 🏗️ P5 0%           │
├──────────┴──────────┴──────────┴──────────┴─────────────────────┤
│  SIDEBAR (260px)    │  MODULE CARDS GRID                        │
│  ─────────────────  │  ─────────────────────────────────────    │
│  🧱 Foundations     │  ┌──────────────┐  ┌──────────────┐      │
│  ▸ DSA        Core  │  │ DSA — Light  │  │ Operating    │      │
│  ▸ OS         Core  │  │ 7 concepts   │  │ Systems      │      │
│  ▸ Networking Core  │  │ ██░░░░░ 28%  │  │ Core   0%    │      │
│  ▸ Linux      Deep  │  └──────────────┘  └──────────────┘      │
│  ...                │  ...                                      │
└─────────────────────┴───────────────────────────────────────────┘
```

**Mobile** — hamburger drawer + single column:
```
┌──────────────────────────┐
│ ☰  Cloud & AI/ML  23% ◉ │  ← sticky header
├────┬────┬────┬────┬──────┤
│ 🧱 │ ⚙️ │ ☁️ │ 🤖 │  🏗️ │  ← icon-only tabs
├────┴────┴────┴────┴──────┤
│ 🧱 FOUNDATIONS · Modules ☰│  ← tap opens drawer
├──────────────────────────┤
│  ┌────────────────────┐  │
│  │ DSA — Light   Core │  │
│  │ 7 concepts  ░░ 0%  │  │
│  └────────────────────┘  │
│  ┌────────────────────┐  │
│  │ Operating Systems  │  │
│  └────────────────────┘  │
└──────────────────────────┘
```

---

## ✨ Features

### 🔖 5 Structured Phases

| Phase | Title | Timeline | What You'll Master |
|-------|-------|----------|--------------------|
| 1 | 🧱 Foundations | Months 1–2 | DSA, OS, Networking, Linux/Bash, Python, SQL, Math |
| 2 | ⚙️ Core ML & Deep Learning | Months 2–4 | PyTorch, CNNs, Transformers, End-to-End Pipelines |
| 3 | ☁️ Cloud + MLOps | Months 4–6 | Docker, Kubernetes, AWS SageMaker, CI/CD, Certifications |
| 4 | 🤖 Modern AI Stack | Months 6–9 | LLMs, RAG Systems, AI Agents, LangChain, Prompt Engineering |
| 5 | 🏗️ Portfolio & Career | Months 9–12 | Projects, System Design, Interviews, Career Strategy |

---

### 📱 Fully Responsive — Mobile + Desktop

Built mobile-first with real CSS media queries — not JavaScript conditionals:

| Feature | Mobile (< 768px) | Desktop (≥ 768px) |
|---------|-----------------|-------------------|
| Sidebar | Slide-in drawer via ☰ hamburger | Always-visible 260px panel |
| Phase tabs | Icon + phase number only | Full icon + title + progress % |
| Card layout | Single column, full width | Auto-fill grid (240px+ cards) |
| Tap targets | Min 44px (Apple/Google standard) | Standard click targets |
| Viewport | `100dvh` — no mobile browser bar overlap | `100dvh` |
| Drawer close | Tap backdrop or select a module | N/A |

---

### 📦 Module Cards

Each phase has multiple learning modules. Every card shows:
- Module title and depth tag (`Deep` / `Core` / `Practical`)
- Total concept count
- Preview of the first 3 concept names with live tick status
- Progress bar showing completion

Tap any card to open the full concept checklist for that module.

---

### ✅ Concept Checklist

Inside each module, every concept has:
- A **name** — the specific topic to learn
- A **detail line** — exactly what to study, which tools, and why it matters on the job
- A **circular checkbox** — tap to mark as learned, fills with the phase colour

Example from *Linux & Bash Mastery*:
```
○  SSH & Remote Work
   ssh keys, scp, rsync, tmux/screen, port forwarding —
   working with remote GPU servers and cloud VMs daily
```
Tap → turns green with ✓, saved to `localStorage` instantly.

---

### 💾 Persistent Progress

Every checkbox is saved to `localStorage` the moment you tap it:

- ✅ Close tab → reopen → everything exactly where you left it
- ✅ Works fully offline after first load
- ✅ Last active phase tab is also restored on reopen
- ✅ `✓ Saved` flash confirms each save on desktop
- ⚠️ Progress is per-browser — Chrome and Firefox store separately

---

### 📊 Live Progress Tracking — 3 Levels

| Level | Location | Tracks |
|-------|----------|--------|
| **Overall** | Top-right ring + % | Every concept across all 5 phases |
| **Per Phase** | Badge on each tab | All concepts within that phase |
| **Per Module** | Sidebar bar + card bar | Concepts within that module |

All bars update instantly on every tap — zero page reload.

---

### 🏷️ Depth Labels

| Label | Colour | Meaning |
|-------|--------|---------|
| `Deep` 🔴 | Red | Master it — tested in interviews, used daily on the job |
| `Core` 🔵 | Blue | Solid conceptual understanding required |
| `Practical` 🟠 | Orange | Build with it — hands-on focus over theory |

---

### 🔄 Reset Button

Clears all progress after a confirmation prompt. Wipes both localStorage keys completely.

---

## 🗂️ Full Module List

<details>
<summary><strong>🧱 Phase 1 — Foundations (click to expand)</strong></summary>

- **DSA — Light & Targeted** `Core` — Arrays, HashMaps, Trees, Graph Traversal, Sorting, Light DP
- **Operating Systems** `Core` — Processes, Memory, File Systems, Signals, Scheduling, Concurrency
- **Networking Fundamentals** `Core` — OSI Model, TCP/IP, DNS, Load Balancers, VPC, Firewalls
- **Linux & Bash Mastery** `Deep` — Navigation, Permissions, Shell Scripting, SSH, systemd, Text Processing
- **Python: Production-Grade** `Deep` — OOP, Async, Type Hints, Testing, Clean Architecture, Profiling
- **SQL & Data Engineering** `Deep` — Advanced SQL, Pipelines, Distributed Storage, NoSQL
- **Linear Algebra** `Core` — Vectors, Matrices, Eigendecomposition, Tensors
- **Probability & Statistics** `Core` — Distributions, Hypothesis Testing, Information Theory
- **Calculus for ML** `Core` — Derivatives, Gradient Descent, Computational Graphs

</details>

<details>
<summary><strong>⚙️ Phase 2 — Core ML & Deep Learning (click to expand)</strong></summary>

- **Classical ML Mastery** `Deep` — Supervised/Unsupervised Learning, Evaluation, Feature Engineering, Tuning
- **PyTorch Deep Dive** `Deep` — Tensors, nn.Module, Training Loops, Optimization, Debugging
- **Neural Network Architectures** `Deep` — CNNs, RNNs/LSTMs, Transformers from Scratch, ViTs, Generative Models
- **End-to-End ML Pipelines** `Practical` — DVC, MLflow, ONNX, Kaggle Strategy

</details>

<details>
<summary><strong>☁️ Phase 3 — Cloud + MLOps (click to expand)</strong></summary>

- **Docker & Containerization** `Deep` — Dockerfile, Networking, Security, GPU Containers
- **Kubernetes for ML** `Core` — Pods, Deployments, Scaling (HPA/KEDA), Helm Charts
- **AWS for ML Engineers** `Deep` — EC2, S3, SageMaker, Glue, Kinesis, Serverless, Cost Optimization
- **CI/CD for ML (MLOps)** `Deep` — ML Pipelines, Model Testing, Drift Monitoring, GitHub Actions, Feature Stores
- **Cloud Certifications** `Practical` — AWS Cloud Practitioner → AWS ML Specialty → GCP Professional ML

</details>

<details>
<summary><strong>🤖 Phase 4 — Modern AI Stack (click to expand)</strong></summary>

- **LLMs: Deep Understanding** `Deep` — Architecture, Fine-tuning (LoRA/QLoRA/RLHF), Inference Optimization, Evaluation
- **RAG Systems (Production)** `Deep` — Chunking, Embeddings, Vector DBs, Hybrid Retrieval, RAGAS Evaluation
- **Agentic AI Systems** `Deep` — ReAct, LangChain, LangGraph, AutoGen/CrewAI, Guardrails, Memory Systems
- **LLM APIs & Prompt Engineering** `Core` — OpenAI/Anthropic APIs, CoT, Cost Optimization, Observability

</details>

<details>
<summary><strong>🏗️ Phase 5 — Portfolio & Career (click to expand)</strong></summary>

- **Portfolio Projects (Tier 1)** `Practical` — Cloud ML API, RAG Chatbot, AI Agent (all deployed)
- **Engineering Best Practices** `Deep` — ML System Design, FastAPI, Observability Stack, Security
- **Interview Preparation** `Practical` — ML System Design, LeetCode, ML Theory, Behavioral (STAR)
- **Career Strategy** `Practical` — GitHub presence, LinkedIn optimisation, Target companies, Open Source

</details>

---

## 🛠️ Tech Stack

| Layer | Technology | Why |
|-------|-----------|-----|
| Language | Vanilla JavaScript (ES6+) | No build step, instant first render on any device |
| Styling | CSS3 with real `@media` queries | Proper responsive design, no JS breakpoint hacks |
| Rendering | Direct DOM manipulation | Zero framework overhead |
| Persistence | Browser `localStorage` | Offline-capable, zero-server progress saving |
| Hosting | GitHub Pages | Free, CDN-backed, HTTPS |

**No React. No Babel. No npm. No node_modules. No build pipeline.**
One `index.html` — open it anywhere and it works instantly.

> The previous v1.x used React 18 + Babel Standalone (~1.2MB runtime that had to compile JSX on the device before anything rendered). v2.0 ships zero runtime dependencies — the browser gets pure HTML, CSS, and JS as intended.

---

## 📝 Changelog

| Version | Change |
|---------|--------|
| `v1.0` | Initial build — React + Babel CDN, desktop layout |
| `v1.1` | localStorage persistence, reset button, save flash |
| `v1.2` | Added CS Fundamentals modules to Phase 1 (DSA, OS, Networking, Linux) |
| `v2.0` | Full rewrite — vanilla JS, real CSS media queries, mobile drawer, zero dependencies |

---

## 🚀 Run Locally

```bash
# Clone
git clone https://github.com/TANMOY-MAITI/roadmap.git
cd roadmap

# Open in browser — no server, no install needed
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or visit the live site → **[tanmoy-maiti.github.io/roadmap](https://tanmoy-maiti.github.io/roadmap)**

---

## 👤 About

Built by **Tanmoy Maiti** — B.Tech CSE (AI/ML), 3rd Year, Kolkata.
Tracking my structured path toward MLOps & Cloud Infrastructure Engineering.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tanmoy_Maiti-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/tanmoy-maiti-161053301/)
[![GitHub](https://img.shields.io/badge/GitHub-TANMOY--MAITI-181717?style=flat&logo=github)](https://github.com/TANMOY-MAITI)

---

## 📄 License

MIT — open source, fork freely.
If you adapt this for your own learning path, a ⭐ on the repo is appreciated!


<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Prabhanjay%20Singh&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20%2F%20ML%20Engineer%20%E2%80%A2%20Deep%20Learning%20%E2%80%A2%20LLMs%20%E2%80%A2%20Computer%20Vision&descAlignY=58&descSize=18" alt="header"/>
</p>

<p align="center">
  <a href="https://github.com/Sharpwarrior86">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=720&lines=Training+deep+learning+models+on+NVIDIA+H200+%F0%9F%9A%80;Shipping+them+to+production+with+ONNX+%E2%9A%A1;Building+LLM+agents+%26+vision+pipelines+%F0%9F%A4%96;Founder+%40+ChessPe+%E2%99%9F%EF%B8%8F" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:prabhu860s@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://huggingface.co/YOUR-HF"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/></a>
  <img src="https://komarev.com/ghpvc/?username=Sharpwarrior86&style=for-the-badge&color=0e75b6&label=Profile+Views" alt="views"/>
</p>

---

## 👋 About Me

```python
class Prabhanjay:
    role       = "AI / ML Engineer"
    building   = "ChessPe — AI chess intelligence platform (Founder & Lead ML Engineer)"
    education  = ["M.Tech, Artificial Intelligence @ Bennett University (2027)",
                  "B.Tech, CSE @ SRM University (2024)"]
    focus      = ["Deep Learning", "Computer Vision", "LLMs & Agents", "MLOps"]
    certified  = ["AWS Certified AI Practitioner", "AWS Certified Cloud Practitioner"]
    published  = "NLP & LLMs for News Classification — IJARIIT, 2024"
    open_to    = "AI / ML Engineer roles 🚀"
```

- 🧠 I train, evaluate and **deploy** deep learning models end to end — data lineage → GPU training → calibrated evaluation → production inference
- ⚡ Trained **6 PyTorch models on an NVIDIA H200** and serve them at **2 ms/position** on CPU via ONNX Runtime
- 🤖 Build **LLM-powered systems** with Claude, Gemini and LangGraph — agents, vision pipelines and hybrid rule + LLM scoring
- ☁️ Director of Events, **AWS Cloud Club** — ran cloud workshops & certification prep for 100+ students

---

## 🏆 Featured Work

### ♟️ ChessPe AI — Six Chess Intelligence Models
`PyTorch` `CUDA` `NVIDIA H200` `bf16` `ONNX Runtime` `INT8` `Stockfish`

Six deep learning models trained on Lichess (CC0) games labelled by Stockfish, with game-separated splits and hash-tracked data lineage to prevent leakage.

| Model | Architecture | Result |
|---|---|---|
| Human move prediction | Rating-conditioned ResNet | **49.3% top-1 / 76.5% top-3** (vs. 6.3% baseline) |
| Tactics detection | Multi-task, multi-label (18 themes) | **84.1% top-1 / 96.6% top-3** |
| Puzzle difficulty | Regression head | **34% lower error** (MAE 271 vs. 413) |
| Position evaluator | 7.3M-param ResNet-SE | **0.92 Pearson** vs. Stockfish |
| Mistake-risk classifier | Calibrated classifier | **0.79 AUROC**, ECE **0.004** |
| Positional regression | ResNet | **R² 0.635** (vs. 0.559 baseline) |

🚀 **Deployment:** ONNX Runtime CPU inference at **2 ms/position** with 100% PyTorch parity · INT8 quantization benchmarked · versioned model registry with model cards

### 📝 ChessPe Platform — Handwritten Score Sheet → PGN
`Gemini Vision` `NestJS` `PostgreSQL` `Redis` `BullMQ` `Next.js` `Docker` `GitHub Actions`

- Computer vision pipeline that reads **handwritten chess score sheets**, validates every move with rule-based legality checks and converts games to PGN
- Async **Stockfish analysis** on BullMQ workers + **LLM-generated coaching reports**
- **58 feature modules**, payments, real-time updates, **160+ test suites**, CI/CD

### 🔍 SiteJaanch — AI Website Intelligence Platform
`FastAPI` `Celery` `Redis` `PostgreSQL` `LLMs`

- Crawl → rules → LLM judgment → scoring pipeline with **66 rule-based checks**
- Calibrated hybrid scoring with LLM influence capped at **15–30%** for reliability · **389 tests**

### 💸 [AI Finance Credit Follow-Up Agent](https://github.com/Sharpwarrior86/Finance-agent)
`LangGraph` `Gemini` `FastAPI` `React` `shadcn/ui`

- Agentic workflow that detects overdue receivables and generates context-aware follow-up emails
- 4-stage tone escalation, human-in-the-loop escalation queue, dry-run mode, audit trail, prompt-injection protection

### 📰 News Classification with NLP & LLMs — *Published Research*
- Financial-news sentiment classifier (positive / negative / neutral) using pretrained LLMs
- 📄 *Published in IJARIIT, Vol. 10, Issue 3, May 2024*

---

## 🛠️ Tech Stack

**🧠 AI / ML**

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
</p>

**🤖 LLMs & Agents**

<p>
  <img src="https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prompt%20Engineering-412991?style=flat-square"/>
</p>

**⚙️ Backend & MLOps**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
</p>

**☁️ Cloud**

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"/>
  <img src="https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white"/>
  <img src="https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white"/>
</p>

---

## 🎖️ Certifications

<p>
  <img src="https://img.shields.io/badge/AWS%20Certified-AI%20Practitioner-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS%20Certified-Cloud%20Practitioner-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Sharpwarrior86&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sharpwarrior86&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="top langs"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Sharpwarrior86&theme=tokyonight&hide_border=true" alt="streak"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Sharpwarrior86&theme=tokyo-night&hide_border=true&area=true" alt="activity graph"/>
</p>

---

## 🔭 Currently Working On

- ♟️ Scaling **ChessPe** — AI coaching built on my own trained models
- 🤖 An **LLM coach agent** with RAG + tool calls to my chess models and Stockfish, with a proper eval suite
- 🤗 Publishing ChessPe models and a live demo on **Hugging Face Spaces**

---

<p align="center">
  <i>💬 Ask me about deep learning, model deployment, LLM agents or chess ♟️</i><br/><br/>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer"/>
</p>

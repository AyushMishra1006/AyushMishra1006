<!-- Header -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&duration=2600&pause=700&color=00F5FF&center=true&vCenter=true&width=860&lines=Hi%2C+I%27m+Ayush+Mishra;AI+%26+Backend+Engineer;I+build+production-grade+AI+systems;Multi-Agent+RAG+%7C+LLMs+%7C+FastAPI+%7C+Vector+Search;Every+decision+is+data-backed." />
</p>

---

```python
class AIEngineer:
    def __init__(self):
        self.name     = "Ayush Mishra"
        self.role     = "AI & Backend Engineer"
        self.stack    = ["Python", "FastAPI", "RAG Pipelines", "Multi-Agent Systems",
                         "Gemini", "FastEmbed", "Vector Search", "Supabase"]
        self.approach = "Test in isolation. Measure everything. Ship what the data approves."
        self.mindset  = "Build. Break. Improve. Repeat."

    def what_i_do(self):
        return "I design AI systems that are fast, reliable, and built the right way."

me = AIEngineer()
print(me.what_i_do())
```

<h3 align="center">
I design <b>intelligent pipelines</b> with structured testing, real telemetry,<br>
and data-backed decisions at every layer — built to scale, not just to demo.
</h3>

---

## 🚀 Current Project — Nexus AI

**Multi-Agent Research Synthesis Engine** — a production-grade RAG pipeline that coordinates four specialised AI agents in parallel, each targeting a different knowledge source, then synthesises a single sourced, attributed answer via Gemini 2.5 Flash.

```bash
$ nexus --status

  Architecture  :  4-Agent parallel RAG  (Wikipedia · ArXiv · Tavily Web · YouTube)
  Pipeline      :  Query rewrite → Parallel fetch → Chunk → Embed → Retrieve → Stream
  LLM           :  Gemini 2.5 Flash  (query rewriting + synthesis)
  Embeddings    :  FastEmbed ONNX / bge-small-en-v1.5  (thread-safe, single instance)
  Chunking      :  Hierarchical parent-child (Wiki) · Atomic (ArXiv) · Topic-shift (Web/YT)
  Retrieval     :  Per-source semantic search → diversity cap → top-12 to LLM
  Streaming     :  FastAPI + SSE → frontend typewriter render
  Database      :  Supabase PostgreSQL  (query logs + user history)

  Validated     :  34 queries  ·  91% GOOD quality  ·  ~33s end-to-end
  Avg sim score :  0.78 across all chunks sent to LLM
  Noise chunks  :  Zero reached LLM  (sim floor enforced across all 34 queries)
```

> Built through a **6-phase testing framework** — each component tested and approved in isolation before the next was assembled. Every architectural decision (chunk size, embedding model, retrieval strategy, timeout caps) is backed by measured data, not intuition.

🔗 [**View Repository →**](https://github.com/AyushMishra1006/Nexus-AI)

---

## 🧠 Engineering Principles

Building scalable, production-ready AI systems requires more than connecting APIs — it requires a methodology.

| Principle | In practice |
|-----------|-------------|
| Component isolation before integration | Each layer (sources, chunking, embeddings, retrieval) tested and validated independently before assembly |
| Data-backed architecture decisions | Chunk size raised 450→750 chars after token distribution showed 115-token avg below retrieval floor — measured, not guessed |
| Measure before optimising | 31 queries of telemetry before setting any timeout cap. ArXiv averaged 12.1s — cap set at 10s based on data |
| Simplicity over complexity | Tested RAPTOR (recursive abstractive clustering) — dropped it. Hierarchical parent-child delivers equivalent quality at zero indexing overhead |
| Graceful degradation over hard failures | Sources that miss their cap are skipped cleanly. Pipeline continues with what it has — no crashes, no empty answers |

---

## ⚡ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,supabase,mongodb,mysql,gcp,git,linux&perline=8" />
</p>

```yaml
AI & LLMs:
  - RAG Pipelines  (multi-agent, production-grade)
  - LLMs: Gemini 2.5 Flash, HuggingFace models
  - Embeddings: FastEmbed ONNX, bge-small-en-v1.5
  - Vector Search: semantic retrieval, cosine similarity, diversity caps
  - Frameworks: LangChain

Backend:
  - FastAPI  (async, SSE streaming, rate limiting)
  - Python   (primary language)
  - Supabase PostgreSQL
  - REST API design

Data & ML:
  - Pandas, NumPy, Scikit-learn
  - TensorFlow, PyTorch, Keras
  - Matplotlib, Seaborn, Plotly, Power BI

Tools & Cloud:
  - Git, Linux
  - Google Cloud Platform
  - MongoDB, MySQL
```

---

## 🧩 Featured Projects

<table>
<tr>
<td width="55%">

### 🔬 Nexus AI — Multi-Agent Research Engine
Production-grade RAG pipeline. 4 specialised agents (Wikipedia, ArXiv, Web, YouTube) running in parallel. Built through a 6-phase testing framework with real telemetry and data-backed architecture decisions.

**Results:** 91% GOOD quality · ~33s end-to-end · 34 queries validated · Zero noise chunks to LLM

**Stack:** Python · FastAPI · Gemini · FastEmbed ONNX · Supabase · SSE Streaming

🔗 [Repository](https://github.com/AyushMishra1006/Nexus-AI)

</td>
<td width="45%">

### 📄 DocMind — AI PDF Summarizer
AI-powered document intelligence using OCR, RAG and LLMs. Upload a PDF, get a structured, sourced summary.

**Stack:** Python · Streamlit · Gemini · RAG · OCR

🔗 [Repository](https://github.com/AyushMishra1006/DocMind-AI-Powered-PDF-Summarizer)

</td>
</tr>
</table>

---

## 🎯 Open To

```yaml
Roles:
  - AI Engineer
  - Backend Engineer  (Python / FastAPI)
  - ML Engineer
  - AI / ML Internships
  - Research Internships

Strengths:
  - Production-grade AI system design
  - Structured testing and validation methodology
  - Real-world RAG pipeline engineering
  - Data-backed decision making at every layer
  - Fast learner — from concept to working system
```

---

## 🌐 Connect

<p align="center">
  <a href="https://linkedin.com/in/ayush-mishra-857123304">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:ayushmishra0605@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

```python
def life():
    while True:
        learn()
        build()
        measure()
        improve()

life()
```

<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AyushMishra1006&label=Profile+Views&color=00F5FF&style=for-the-badge" />
</p>

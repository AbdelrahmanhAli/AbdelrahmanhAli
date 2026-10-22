<h1 align="center">Abdelrahman Hamdy</h1>

<p align="center">
  <b>AI Engineer</b> — agentic systems, retrieval, and the backend that makes them usable.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abdelrahmann-hamdyy"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:Abdelrahmanhamdy01@aswu.edu.eg"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Aswan,_Egypt-333333?style=flat-square&logo=googlemaps&logoColor=white" alt="Aswan, Egypt">
</p>

I build LLM systems where retrieval, the agent loop, and the API around them are
engineered rather than demoed: explicit state, typed tool calls, tests that run
without an API key, and READMEs that state the trade-offs.

---

## Selected work

### [RAG Techniques — 15 runnable repositories](https://github.com/AbdelrahmanhAli/rag-techniques-collection)

A from-scratch tour of retrieval design: multi-query, RAG-Fusion, HyDE,
step-back prompting, query decomposition, logical routing, structured queries,
multi-representation indexing, RAPTOR-lite, ColBERT, cross-encoder re-ranking,
extractive and contextual compression, and hybrid BM25 + dense search.

Each repository is standalone — its own `core.py`, sample corpus, README, and
**offline tests** that use deterministic fake embeddings, so the suite needs no
key and no network. Start with
[`rag-from-scratch`](https://github.com/AbdelrahmanhAli/rag-from-scratch).

`Python` · `LangChain v1` · `Chroma` · `rank-bm25` · `RAGatouille` · `pytest` · `ruff`

### [Multi-Agent Scientific Research System](https://github.com/AbdelrahmanhAli/muti-agent-Scientific-research-system)

LangGraph supervisor and handoff workflows coordinating research, reviewer,
writer, and coder agents over shared state. Includes RAG over Chroma, FAISS, and
pgvector, web and arXiv retrieval, and a FastAPI entry point.

`LangGraph` · `LangChain` · `FastAPI` · `pgvector`

---

## How I build

- **Typed boundaries instead of prompt glue.** Pydantic schemas and `Literal`
  routes in place of substring-matching model output.
- **Retrieval is a design decision.** Chunking, fusion, and re-ranking are chosen
  per corpus, and the cost is measured — not defaulted.
- **Tests before trust.** Offline harnesses exercise the full path with fake
  models, so a failure is reproducible without spending tokens.
- **Docs that admit limits.** Every demo says what it does *not* solve.

## Tools

The tools behind the repositories above:

**LLMs & agents**

<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square" alt="LangChain">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square" alt="OpenAI">
</p>

**Retrieval**

<p>
  <img src="https://img.shields.io/badge/Chroma-FF6B35?style=flat-square" alt="Chroma">
  <img src="https://img.shields.io/badge/BM25-555555?style=flat-square" alt="BM25">
  <img src="https://img.shields.io/badge/ColBERT-555555?style=flat-square" alt="ColBERT">
  <img src="https://img.shields.io/badge/sentence--transformers-555555?style=flat-square" alt="sentence-transformers">
</p>

**Backend**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square" alt="FastAPI">
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square" alt="SQLAlchemy">
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square" alt="Pydantic">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square" alt="SQLite">
</p>

**Infrastructure & testing**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square" alt="pytest">
  <img src="https://img.shields.io/badge/Ruff-D7FF64?style=flat-square" alt="Ruff">
</p>

<sub>Also worked with: Django/DRF, n8n, AWS, Kubernetes.</sub>

## Currently

Software engineer at **Alef for Software Development**, deepening retrieval
evaluation and agent observability.

## Contact

Open to AI engineering roles — [LinkedIn](https://www.linkedin.com/in/abdelrahmann-hamdyy)
or [Abdelrahmanhamdy01@aswu.edu.eg](mailto:Abdelrahmanhamdy01@aswu.edu.eg).

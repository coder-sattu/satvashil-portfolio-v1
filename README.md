<<<<<<< HEAD
# satvashil-portfolio-v1
AI engineering portfolio showcasing Agentic AI, Compound AI, RAG, and LLM-based applications. Building production-ready AI systems and intelligent solutions for real-world problems.
=======
# 🤖 Satvashil Bhosale — Agentic AI Portfolio

> High-performance, 3D interactive portfolio showcasing production **Agentic AI**, **LangGraph Multi-Agent Systems**, **LLM Evaluation (RAGAS / LLM-as-a-Judge)**, and **AI Safety Guardrails**.

---

## 🌟 Key Features & Architecture

- **🤖 3D Interactive Agent Core**: Built with Three.js rendering a cybernetic agent chassis with real-time FPS & telemetry HUD overlays.
- **⚡ Interactive Workflow Graphs**: Directed state machine graphs detailing multi-agent routing, tool execution, critique loops, and guardrails.
- **🔬 LLM Evaluation & Benchmarking**: Dedicated showcase for RAGAS triad metrics (*Faithfulness, Relevance, Precision*), LLM-as-a-Judge, G-Eval, and MLflow/LangSmith observability.
- **🛡️ AI Safety & Guardrails Engine**: Input/output validation using NeMo Guardrails, Llama Guard intent classification, PII scrubbing, and factual hallucination shields.
- **📱 Responsive & Dark-Mode Design**: Cyber-futuristic aesthetic with glassmorphism, fluid typography (Bricolage Grotesque & IBM Plex Mono), and mobile navigation drawer.

---

## 🛠️ Technical Arsenal

| Category | Frameworks & Tools |
| :--- | :--- |
| **Agentic AI & Orchestration** | LangGraph, LangChain, CrewAI, OpenAI API, Anthropic Claude, Groq LPU (Llama 3), Ollama |
| **LLM Evaluation & Metrics** | RAGAS, LLM-as-a-Judge, G-Eval, DeepEval, LangSmith Evals, MLflow GenAI Eval |
| **Safety & Guardrails** | NeMo Guardrails, Guardrails AI, Llama Guard, Prompt Injection Defense, PII Scrubbing, Pydantic |
| **Data & Lakehouse** | Apache Spark, Vector Search, Delta Lake, Unity Catalog, DuckDB, Polars, Neo4j GraphRAG |
| **Vector Databases** | ChromaDB, Pinecone, Qdrant, FAISS, Hybrid Search & Cross-Encoder Reranking |
| **Computer Vision & Audio** | YOLOv8, OpenCV, TensorRT, NVIDIA Jetson, Whisper STT, AWS Polly, Twilio Voice |
| **Core Engineering** | Python, FastAPI, React, Three.js, Docker, PostgreSQL, MongoDB, Git |

---

## 📁 Repository Structure

```text
├── index.html               # Main single-page portfolio (React + Babel + Three.js)
├── satvashil-portfolio.html  # Synchronized production HTML build
├── photo.jpg                # Profile portrait
├── commands.txt             # Local serve command helper
├── render.yaml              # Render Blueprint deployment configuration
└── README.md                # Project documentation
```

---

## 🚀 Local Quickstart

No build tools or bundlers required. Run locally using Python's built-in HTTP server:

```bash
# 1. Clone the repository
git clone https://github.com/coder-sattu/Portfolio.git
cd Portfolio

# 2. Start local server
python -m http.server 8000
```

Open your browser and navigate to `http://localhost:8000`.

---

## ☁️ Deployment on Render

This repository includes a [`render.yaml`](./render.yaml) file for 1-click static site deployment.

1. Push this repository to **GitHub**.
2. Go to [Render Dashboard](https://dashboard.render.com/) $\rightarrow$ **New +** $\rightarrow$ **Blueprint**.
3. Select your repository. Render will automatically detect `render.yaml` and launch your live site.

---

## 📬 Contact & Connect

- **Email**: [satvashilbwork@gmail.com](mailto:satvashilbwork@gmail.com)
- **LinkedIn**: [linkedin.com/in/satvashil-bhosale-17730a27a](https://linkedin.com/in/satvashil-bhosale-17730a27a)
- **GitHub**: [@coder-sattu](https://github.com/coder-sattu)

---
*© Satvashil Bhosale. All rights reserved.*
>>>>>>> a92e9cf (Initial commit: Satvashil Bhosale Agentic AI Portfolio)

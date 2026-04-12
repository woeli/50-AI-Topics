#  50 AI — Weekly Concept Notebooks

> The purpose of this repo is to explore each week an AI concept and create a notebook on it.

---

## Repository Structure

Notebooks are organised by **AI topic**, making it easy to navigate by area of interest.

```
50-AI-Topics/
├── guardrails/          ← Safety, alignment & adversarial attacks
│   └── Jailbreaking.ipynb
├── rag/                 ← Retrieval-Augmented Generation
│   └── ICR_RAG.ipynb
├── architecture/        ← Architecture & Internal Working Logics of LLMs
│   └── KV_Cache.ipynb
│   └── Lottery_Ticket_Hypothesis.ipynb
├── agenitc/        ← Agentic System
│   └── dynamic_vertical_agent_creation.ipynb
├── assets/              ← Shared images & diagrams
├── TEMPLATE.ipynb       ← Reusable notebook template
└── README.md
```


---

## Notebook Index

| Topic Area | Notebook | Key Concepts |
|---|---|---|
| Guardrails | [Jailbreaking](./guardrails/Jailbreaking.ipynb) | Direct manipulation, Conversational manipulation, GCG, PAIR, Activation Steering |
| RAG | [ICR-RAG](./rag/ICR_RAG.ipynb) | Iterative retrieval, Context enrichment, Query reformulation, Lost-in-the-Middle problem |
| Architecture | [KV Cache](./architecture/KV_Cache.ipynb) | Attention mechanism, QKV, Memory efficiency, Inference optimization |
| Agentic System | [Dynamic Vertical Agent Creation](./agentic/dynamic_vertical_agent_creation.ipynb) | Agent architecture, Dynamic agent creation, Task decomposition, Agent orchestration |
| Lottery Ticket Hypothesis | [Lottery Ticket Hypothesis](./architecture/Lottery_Ticket_Hypothesis.ipynb) | Lottery Ticket Hypothesis, Pruning, Rewinding, Subnetworks |

---

## Notebook Structure

Every notebook follows the same 5-section methodology:

| # | Section | Purpose |
|---|---------|---------|
| 0 | **Header** | Title, badges, one-line TL;DR |
| 1 | **Overview** | What is it and why does it matter? |
| 2 | **How It Works** | Step-by-step breakdown with diagrams |
| 3 | **Advantages & Limitations** | Balanced evaluation table |
| 4 | **Code Example** | Minimal, runnable demo + production-ready version |
| 5 | **Key Takeaways** | Bullet-point summary |


---

## 🚀 Getting Started

### Run locally
```bash
git clone https://github.com/woeli/50-AI-Topics
cd 50-AI-Topics
pip install jupyter
jupyter notebook
```

### Dependencies
- **Production examples** list their requirements in a `Prerequisites` table at the top of the notebook

---

## Using the Template

To start a new notebook:

1. Copy `TEMPLATE.ipynb` into the relevant topic folder (create the folder if it doesn't exist):
   ```bash
   cp TEMPLATE.ipynb agentic/ReAct_Agent.ipynb
   ```
2. Fill in each section — placeholder comments guide you through what to write
3. Drop any diagrams into `assets/` and reference them with `../assets/your_image.png`
4. Add your notebook to the index table in this README

---

## About

This project is inspired by the [100-Days-of-ML](https://github.com/Avik-Jain/100-Days-Of-ML-Code) format — one focused, practical notebook per topic, designed to be readable in under 30 minutes and runnable end-to-end.

**Author:** E. Wolf · [GitHub](https://github.com/woeli)

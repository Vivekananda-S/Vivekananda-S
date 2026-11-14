# Vivekananda Shonti

**Senior Engineer, Data & AI** at Tiger Analytics, based in Hyderabad. I build AI agents and the systems that check their work: agentic AI, ML systems, and MLOps.

[LinkedIn](https://www.linkedin.com/in/vivekanandashonti)

## What I'm building

### [Agent Trust Layer](https://github.com/Vivekananda-S/agent-trust-layer)

A small, calibrated judge model that reads an AI agent's execution trace and says whether the agent failed, and how. It is meant to replace a frontier LLM as the judge on every run.

- **Status:** in progress. The dataset and frozen evaluation splits are done, labelling is under way, and no judge is trained yet.
- **Data:** 2,087 agent traces from customer-service tasks, split by task, with one agent model held out of training entirely.
- **Taxonomy:** eight failure classes, from invented tool arguments to prompt injection.
- **Budget:** collected on one rented GPU for about $28, capped by a cost ledger.

The [results log](https://github.com/Vivekananda-S/agent-trust-layer/blob/main/docs/results.md) records every decision and mistake, including a benchmark pass signal that turned out to be wrong in both directions.

## Other projects

| Project | What it does |
|---|---|
| [SQL agent](https://github.com/Vivekananda-S/langchain-sql-agent) | An agent that answers plain-English questions about a database. It looks up the schema, writes a SQL query, checks that the query is read-only, runs it, and repairs the query if it fails. Built with LangChain and Gemini. |
| [Leaf disease detection](https://github.com/Vivekananda-S/PlantDiseasePrediction) | A convolutional network that classifies 15 potato, tomato and pepper leaf conditions from a photo. Served through FastAPI with TensorFlow Serving and a Google Cloud Function, with a React web app and a React Native mobile app. |
| [Virtual keyboard and mouse](https://github.com/Vivekananda-S/Virtual_Key_Board) | Type and move the cursor with hand gestures in front of a webcam, using OpenCV and MediaPipe hand tracking. |

## Background

- Before Tiger Analytics I worked at Virtusa, building generative AI systems and Python automation, including an LLM document-intelligence system that halved ticket creation time for a 200-person team.
- Google Cloud certified Professional Machine Learning Engineer.
- B.Tech in Computer Science and Engineering, MLR Institute of Technology, Hyderabad.

## Tools I use

**Generative AI:** LLMs, RAG pipelines, LangGraph, LangChain, LangSmith, vector search (FAISS, Vertex AI Vector Search)<br>
**Machine learning:** QLoRA fine-tuning, embeddings, Hugging Face Transformers, TensorFlow, evaluation and calibration<br>
**Cloud and MLOps:** Google Cloud (Vertex AI, Cloud Run functions, Pub/Sub, BigQuery), Docker, CI/CD, vLLM, Modal<br>
**Backend:** Python, FastAPI, REST APIs, event-driven services, SQL, pytest

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Vivekananda-S&theme=github_dark">
  <img alt="Contribution activity over the past year" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Vivekananda-S&theme=default">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Vivekananda-S&theme=dark&hide_border=true">
  <img alt="Total contributions and contribution streak" src="https://streak-stats.demolab.com?user=Vivekananda-S&theme=default&hide_border=true" height="170">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Vivekananda-S&theme=github_dark">
  <img alt="Languages by commit share" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Vivekananda-S&theme=default" height="170">
</picture>

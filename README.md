# Wyctor Fogos da Rocha

**AI / ML Engineer** — from research to production.

I build LLM-based systems and multimodal pipelines that run in production, with end-to-end MLOps: fine-tuning, containerised serving, monitoring. My peer-reviewed research (incl. *Scientific Reports*, *IEEE JBHI*) grounds the engineering in statistical rigour.

Currently at **Tribunal de Justiça do Espírito Santo (TJES)**, where I built [LuzIA](https://wyctor.com.br/experience) — an LLM-powered document analysis system that cut ruling review from 10 to 2 minutes and was selected by Brazil's National Council of Justice (CNJ) for nationwide rollout.

🌐 [wyctor.com.br](https://wyctor.com.br) · [LinkedIn](https://www.linkedin.com/in/wyctorfogos/) · [Google Scholar](https://scholar.google.com/citations?user=NGT_KVYAAAAJ&hl=en) · [ORCID](https://orcid.org/0000-0002-1909-7274)

---

## What I'm working on

- **LLM systems for the judiciary** — multi-stage NLP pipelines (extraction, cross-encoder re-ranking, hybrid scoring) for legal document classification, served with FastAPI + RabbitMQ + vLLM + Docker.
- **Multimodal medical AI** — gated cross-attention architectures for skin lesion classification, published at IJCNN 2026 (IEEE WCCI) and in Scientific Reports (Nature Portfolio).
- **LLM-driven neural architecture search** — using local LLMs as NAS controllers under deployment constraints (SIBGRAPI 2026).

---

## Featured projects

| Project | What it does | Links |
|---|---|---|
| **anon-lib** | PII detection & masking for pt-BR and English — hybrid regex + local LLM, 21 pt-BR / 7 EN entity types, first library to support the 2026 alphanumeric CNPJ. | [PyPI](https://pypi.org/project/anon-lib/) · [GitHub](https://github.com/wyctorfogos/anon-lib) |
| **RAG-DOCS-with-PGVECTOR** | Retrieval-augmented generation over documents, embeddings stored in Postgres via pgvector. | [GitHub](https://github.com/wyctorfogos/RAG-DOCS-with-PGVECTOR) |
| **RG-DermNet** | Residual gated-attention multimodal fusion for skin lesion classification — AUC 0.95 ± 0.01 on PAD-UFES-20. | [Paper (IJCNN 2026)](https://linklings.s3.amazonaws.com/organizations/WCCI/wcci2026/submissions/stype114/kM46h-ijcnn_pap4428s2.pdf) |
| **LLM-as-NAS-controller** | Neural architecture search driven by a local LLM served through Ollama. | [GitHub](https://github.com/wyctorfogos/llm-as-nas-controller) |
| **Fine-tuning Gemma 3 1B** | LoRA fine-tuning with Unsloth, exported for vLLM inference. | [GitHub](https://github.com/wyctorfogos/Fine-tunning-Gemma3-1b-unsloth) |
| **NER** | Named entity recognition with a BERT-based model for text anonymisation. | [GitHub](https://github.com/wyctorfogos/NER) |

> More repos: [github.com/wyctorfogos?tab=repositories](https://github.com/wyctorfogos?tab=repositories)

---

## Selected publications

- **PRISM** — clinically interpretable stepwise framework for multimodal skin cancer diagnosis. *Scientific Reports* (Nature Portfolio), 2026. [DOI](https://doi.org/10.1038/s41598-026-47756-4)
- **RG-DermNet** — multimodal attention-based model for skin lesion classification. *IJCNN 2026* (IEEE WCCI). [Preprint](https://linklings.s3.amazonaws.com/organizations/WCCI/wcci2026/submissions/stype114/kM46h-ijcnn_pap4428s2.pdf)
- **MetaBlock-SE** — handling missing metadata via sentence embeddings. *IEEE JBHI*, 2025. [DOI](https://doi.org/10.1109/JBHI.2025.3612837)
- **LLM-driven NAS** — architecture search under deployment constraints. *SIBGRAPI 2026*. [GitHub](https://github.com/wyctorfogos/llm-as-nas-controller)

Full list: [wyctor.com.br/publications](https://wyctor.com.br/publications)

---

## Tech stack

**Languages:** Python (production-level), SQL, JavaScript  
**ML & LLM:** PyTorch, Hugging Face Transformers, LLM fine-tuning (LoRA/PEFT), RAG, cross-encoders, vLLM, Ollama, OpenCV, MLflow  
**Backend & infra:** FastAPI, Flask, gRPC, Docker, RabbitMQ, Kafka, PostgreSQL, Azure, Git  
**Data:** PySpark, Pandas, NumPy

---

## Education

- **M.Sc., Informatics — Data Science and AI** · Federal University of Espírito Santo (UFES), 2026  
- **Télécom SudParis, France** · M2 TRIED coursework, BRAFITEC exchange, 2021–2022 (63 ECTS)  
- **B.Sc., Electrical Engineering** · Federal Institute of Espírito Santo (IFES), 2023

---

📫 **wyctor.fogos@gmail.com** · Based in Vitória, Brazil · Trilingual: Portuguese · English · French

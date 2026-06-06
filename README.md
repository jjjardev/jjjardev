---

## Jessie James T. Jarder

**BSIT — Negros Occidental, Philippines**

Built the first sentiment dataset for Hiligaynon and a sub-2B LLM orchestration system that runs on a 10-year-old laptop. Focused on low-resource NLP and edge AI.

---

### Headline Work

#### [HiliSenti](https://github.com/jjjardev/hilisenti) — First sentiment dataset for Hiligaynon

[![HF Dataset](https://img.shields.io/badge/🤗%20Dataset-HiliSenti--v1-yellow)](https://huggingface.co/datasets/jjjardev/hilisenti-v1)
[![DOI](https://img.shields.io/badge/DOI-10.57967%2Fhf%2F8737-blue)](https://doi.org/10.57967/hf/8737)

- 23,337 sentences · 3 classes · XLM-RoBERTa-large at **93.5% accuracy / 93.4% macro F1**
- Multi-domain corpus: news, social media, translated reviews, synthetic edge cases
- Built on free Colab + free Google Drive; dataset on HF with permanent DOI
- ACL submission in progress

#### [edge-llm-orchestration](https://github.com/jjjardev/edge-llm-orchestration) — LLM orchestration under hard edge constraints

- Sub-2B models (`qwen2.5:1.5b`, `LiquidAI/lfm2.5-1.2b-instruct`) via Ollama
- i3-1305U + 1.5 GB free RAM + no cloud · single-file Python CLI with 4 modes
- Neuro-symbolic per-slot scope-locked validator with empirical v0→v3 failure taxonomy
- ~2,200 lines of docs in `docs/`: scope, architecture, validation, history, related work, reflection

---

### What I Work On

- **Low-resource NLP for Filipino / Visayan languages** — dataset creation, baseline fine-tuning, evaluation rigor
- **Edge AI orchestration** — small models, hardware-aware engineering, no-cloud deployments
- **Zero-dependency tooling** — single-file Python utilities where the stdlib is enough
- **Honest engineering** — I document what didn't work and why (see [reflection](https://github.com/jjjardev/edge-llm-orchestration/blob/main/docs/reflection.md))

---

### Tech Stack

- **ML / Data:** PyTorch · Transformers · Hugging Face · scikit-learn · pandas · NumPy
- **Systems:** Linux (Ubuntu daily driver) · Docker · SSH · Git · Colab · SQLite · Ollama
- **Languages:** Python · SQL · Bash · HTML/CSS/JS (demo UIs only)
- **Models fine-tuned or deployed:** XLM-RoBERTa-large · Qwen2.5-1.5B · LFM2.5-1.2B

---

### Contact

- **Email:** jj.jarder.dev@gmail.com
- **Hugging Face:** [jjjardev](https://huggingface.co/jjjardev)

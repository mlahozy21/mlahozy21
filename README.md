# Marcos Lahoz Yago

**AI researcher / PhD applicant.** M2 in Mathematics & Artificial Intelligence at
Université Paris-Saclay. I work at the intersection of machine learning, deep learning
and statistical inference — LLMs and their interpretability, NLP, graph neural networks,
Bayesian methods and time-series forecasting — with a focus on work that is both
principled and reproducible.

## Selected projects

- **[Interpreting LoRA Fine-Tuning](https://github.com/mlahozy21/Interpreting-LoRA-Fine-Tuning)** — an interpretability study of *what* LoRA changes inside an LLM: where it puts its capacity (per-module update norm + effective rank) and how much it shifts the representations (layer-wise drift), with rank/module ablations (paper + code).
- **[Bayesian Learning of Neural Interactions](https://github.com/mlahozy21/Bayesian-Learning-of-Neural-Interactions)** — Bayesian filtering that recovers the interaction structure of a network of neurons from their spike times: exact posterior, consistency with a CLT rate, and an SMC extension (theory + paper + code).
- **[Structural Probes for Spanish Syntax](https://github.com/mlahozy21/Structural-Probes-for-Spanish-Syntax)** — probing multilingual BERT for Spanish dependency syntax (UD AnCora), with an orthogonal/isometric-probe extension and a layer-wise analysis.
- **[Fine-Tuning Qwen2.5 with LoRA](https://github.com/mlahozy21/Fine-Tuning-Qwen2.5-with-LoRA)** — LoRA / QLoRA instruction-tuning of an LLM (PEFT), a compact Colab-ready pipeline with a base-vs-fine-tuned comparison.
- **[GPT from Scratch](https://github.com/mlahozy21/GPT-from-Scratch)** — a modern decoder-only Transformer (RoPE, RMSNorm, SwiGLU, KV-cache) implemented and trained from scratch in PyTorch, validated on a copy task.
- **[LLM Agent Toolbox](https://github.com/mlahozy21/LLM-Agent-Toolbox)** — building blocks for LLM multi-agent systems: semantic top-k tool selection (embeddings + recall@k evaluation) and a blackboard coordination primitive with a controller that runs agents to quiescence.
- **[Medical RAG with Knowledge Graphs](https://github.com/mlahozy21/Medical-RAG-Knowledge-Graphs)** — multimodal medical Retrieval-Augmented Generation (ColPali + Gemini + a Mondo Knowledge Graph), evaluated on the MIRAGE benchmark.
- **[Fine-Tuning Self-Supervised Speech Models for ASR](https://github.com/mlahozy21/Fine-Tuning-Self-Supervised-Speech-Models-for-ASR)** — fine-tuning Wav2Vec2/MMS with a CTC head on FLEURS, plus a linear-probe study of phonetic content.
- **[Neural Language Modeling: N-Gram vs LSTM](https://github.com/mlahozy21/Neural-Language-Modeling-Ngram-vs-LSTM)** — from-scratch word-level LMs in PyTorch compared by perplexity.
- **[Graph Convolutional Networks (from scratch)](https://github.com/mlahozy21/Graph-Convolutional-Networks-GCN)** — reproduction of Kipf & Welling (2017) with an over-smoothing study.
- **[Production RAG Service](https://github.com/mlahozy21/production-rag-service)** — a production-style Retrieval-Augmented Generation service: retrieval + pluggable LLM backend, guardrails (injection / low-confidence refusal / citations), per-query latency-token-cost observability, and an evaluation harness (recall@k, faithfulness, citation accuracy). FastAPI + Streamlit + tests + CI.
- **[Churn Prediction (MLOps)](https://github.com/mlahozy21/Churn-Prediction-MLOps)** — an end-to-end production-style pipeline: scikit-learn model, FastAPI serving, Docker, CI and permutation-based explainability (real Telco data, test AUC ≈ 0.82).
- **Electricity demand forecasting** — the same problem with two methodologies: [deep learning](https://github.com/mlahozy21/Deep-Learning-Electricity-Demand-Forecasting) (multi-output neural nets) and [statistical models](https://github.com/mlahozy21/Electricity-Demand-Forecasting-Statistical-Models) (GAM/Kalman, quantile GAMs, expert aggregation in R).

## Contact

- Email: marcoslahozy14@gmail.com
- LinkedIn: [marcos-lahoz](https://www.linkedin.com/in/marcos-lahoz-859a98248)

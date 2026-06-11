# Marcos Lahoz Yago

**AI researcher / PhD applicant.** M2 in Mathematics & Artificial Intelligence at
Université Paris-Saclay. I work at the intersection of machine learning, deep learning
and statistical inference — LLMs and their interpretability, multimodality, NLP, graph
neural networks, Bayesian methods and time-series forecasting — with a focus on work
that is both principled and reproducible.

## Selected projects

- **[Interpreting LoRA Fine-Tuning](https://github.com/mlahozy21/Interpreting-LoRA-Fine-Tuning)** — an interpretability study of *what* LoRA changes inside an LLM: where it puts its capacity (per-module update norm + effective rank) and how much it shifts the representations (layer-wise drift), with rank/module ablations — extended to a second model family and to **DoRA** (diagnostically indistinguishable from LoRA), with behavioural validation (report + code + tests).
- **[Video Modality Diagnostics](https://github.com/mlahozy21/video-modality-diagnostics)** — a model-agnostic harness measuring **modality usage and collapse** in multimodal QA (ablations, blind baseline, collapse gap, corruption curves). Measured on Qwen2.5-VL over real NExT-QA frames (n=240): video helps *descriptive* questions (+0.34) but barely *temporal* ones (+0.03), and the frame order is never used — a quantified bag-of-frames bias, per question type.
- **[Medical RAG with Knowledge Graphs](https://github.com/mlahozy21/Medical-RAG-Knowledge-Graphs)** — multimodal medical Retrieval-Augmented Generation (ColPali + Gemini + a Mondo Knowledge Graph), evaluated on the MIRAGE benchmark.
- **[LLM Agent Toolbox](https://github.com/mlahozy21/LLM-Agent-Toolbox)** — building blocks for LLM multi-agent systems: semantic top-k tool selection (embeddings + recall@k evaluation) and a blackboard coordination primitive with a controller that runs agents to quiescence.
- **[GPT from Scratch](https://github.com/mlahozy21/GPT-from-Scratch)** — a modern decoder-only Transformer (RoPE, RMSNorm, SwiGLU, KV-cache) implemented and trained from scratch in PyTorch, validated on a copy task.
- **[Bayesian Learning of Neural Interactions](https://github.com/mlahozy21/Bayesian-Learning-of-Neural-Interactions)** — Bayesian filtering that recovers the interaction structure of a network of neurons from their spike times: exact posterior, consistency with a CLT rate, and an SMC extension (theory + report + code).
- **[Structural Probes for Spanish Syntax](https://github.com/mlahozy21/Structural-Probes-for-Spanish-Syntax)** — probing multilingual BERT for Spanish dependency syntax (UD AnCora), with an orthogonal/isometric-probe extension and a layer-wise analysis.
- **[Graph Convolutional Networks (from scratch)](https://github.com/mlahozy21/Graph-Convolutional-Networks-GCN)** — reproduction of Kipf & Welling (2017) with an over-smoothing study (standard vs residual, 2→16 layers).
- **[Churn Prediction (MLOps)](https://github.com/mlahozy21/Churn-Prediction-MLOps)** — an end-to-end production-style ML project: scikit-learn pipeline + gradient boosting (test AUC ≈ 0.82 on real IBM Telco), FastAPI serving, Docker, MLflow tracking, pytest and GitHub Actions CI, with permutation-based explainability.
- **Electricity demand forecasting** — the same problem with two methodologies: [deep learning](https://github.com/mlahozy21/Deep-Learning-Electricity-Demand-Forecas
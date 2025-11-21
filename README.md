# fullstack-llm-mlops-invoiceProcessing
End-to-end open-source LLM production system: data ingestion → labeling → training → vLLM serving → monitoring → drift → retraining. A complete blueprint for real-world GenAI MLOps.



A fully open-source, production-grade LLM pipeline built from scratch.
This project demonstrates the entire lifecycle of a real GenAI/ML system: ingesting documents, generating labels with Azure OpenAI, training a fine-tuned invoice extraction model using HuggingFace + LoRA, serving it with vLLM/TGI, monitoring production metrics with Prometheus/Grafana, detecting drift, running canary/shadow deployments, and triggering automated retraining through Airflow/Prefect.

The goal is simple: show how modern LLM systems are actually built and run in real companies — with the same engineering discipline used in high-scale ML platforms.

This repository contains:

• Document ingestion + parsing pipelines
• LLM-powered labeling workflows
• Dataset versioning and schema validation
• Fine-tuning with PEFT/LoRA + MLflow tracking
• Multi-backend inference (AOAI, HF, quantized, vLLM, TGI)
• High-performance serving with batching, caching, autoscaling
• Production monitoring, logging, metrics, drift detection
• Canary rollout, shadow deployment, safe model promotion
• Automated retraining and human-feedback loops
• Complete architecture diagrams, runbooks, docs, and open issues

It’s not a toy example — it’s a template for real production GenAI systems.

Perfect for:
• ML engineers who want end-to-end MLOps skills
• GenAI developers preparing for senior roles
• Companies wanting a reference architecture
• Anyone learning how to ship LLM systems responsibly

Everything is built openly, tracked through GitHub Issues, Milestones, and Projects so you can follow the full engineering process from idea → implementation → deployment.

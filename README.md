<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Manuel García Sanz · AI Architect · LLM platforms · On-prem & hybrid AI" src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://manuelgs.com"><img alt="Website" src="https://img.shields.io/badge/manuelgs.com-1f6feb?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjEwIi8%2BPHBhdGggZD0iTTIgMTJoMjBNMTIgMmExNSAxNSAwIDAgMSAwIDIwTTEyIDJhMTUgMTUgMCAwIDAgMCAyMCIvPjwvc3ZnPg%3D%3D"></a>
  <a href="https://www.linkedin.com/in/manuel-garcia-sanz-9555a484/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0xNiA4YTYgNiAwIDAgMSA2IDZ2N2gtNHYtN2EyIDIgMCAwIDAtNCAwdjdoLTR2LTdhNiA2IDAgMCAxIDYtNnoiLz48cmVjdCB4PSIyIiB5PSI5IiB3aWR0aD0iNCIgaGVpZ2h0PSIxMiIvPjxjaXJjbGUgY3g9IjQiIGN5PSI0IiByPSIyIi8%2BPC9zdmc%2B"></a>
  <a href="https://huggingface.co/manuelgscom"><img alt="Hugging Face" src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"></a>
  <a href="mailto:contacto@manuelgs.com"><img alt="Email" src="https://img.shields.io/badge/contacto@manuelgs.com-8250df?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxyZWN0IHg9IjIiIHk9IjQiIHdpZHRoPSIyMCIgaGVpZ2h0PSIxNiIgcng9IjIiLz48cGF0aCBkPSJtMjIgNi0xMCA3TDIgNiIvPjwvc3ZnPg%3D%3D"></a>
  <img alt="Location" src="https://img.shields.io/badge/Valencia_·_Remote_(CET)-30363d?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0yMCAxMGMwIDYtOCAxMi04IDEycy04LTYtOC0xMmE4IDggMCAwIDEgMTYgMHoiLz48Y2lyY2xlIGN4PSIxMiIgY3k9IjEwIiByPSIzIi8%2BPC9zdmc%2B">
</p>

## About me

Computer Engineer (UPV) with **15 years** building mission-critical, low-latency systems in **C++ and Linux**. Today I design and ship AI platforms **end to end**: data, fine-tuning, evaluation, optimized GPU inference and operations, on-prem, in the cloud or hybrid.

A hands-on architect: I decide on measured data (latency, cost, quality) and know what to automate, what a person should review and what data must never leave the client. My recurring pattern: **small specialized models that beat generalists 10× their size**, with the critical decisions made by deterministic code.

## Open source

| Project | What it does | Measured result |
|---|---|---|
| [**dale**](https://github.com/manuelgscom/dale) | Natural language → Linux commands. 100% offline, one native C++ binary for CPU and GPU. | Fine-tuned **0.8B: 79.4%** vs 62.8% for Qwen3.5-9B on 471 cases; 1.7 s median on a 2020 laptop CPU. A deterministic shell analyzer catches 100% of 917 dangerous commands. |
| [**askmdb**](https://github.com/manuelgscom/askmdb) | Natural language → read-only MongoDB queries. 100% offline, native C++ binary. | Fine-tuned **0.8B: 83.6%** vs 47.8% for Qwen3.5-9B on 500 questions over 10 unseen databases, scored by execution. Read-only enforced by a BSON verifier, not by the model. |
| [**llama-server-native**](https://github.com/manuelgscom/llama-server-native) | llama.cpp's server compiled natively for your GPU in Docker, with private web search (SearXNG + MCP). | **2.5× more tokens/s** on a 27B model (5.7 → 14.5 tok/s on an RTX 5070 Ti) by tuning context, KV cache and VRAM. |

## Published models

All in GGUF on [huggingface.co/manuelgscom](https://huggingface.co/manuelgscom), with their benchmarks.

| Models | Task | Fine-tuned accuracy | Base model |
|---|---|---|---|
| dale · 0.8B · 2B · 4B · 9B | Natural language → bash | 79.4 · 81.7 · 87.0 · **89.2%** | Qwen3.5-9B: 62.8% |
| askmdb · 0.8B · 2B · 4B · 9B | Natural language → MongoDB | 83.6 · 86.8 · 89.6 · **91.6%** | Qwen3.5-9B: 47.8% |
| FactuSight · 2B · 4B · 9B (VLM) | Invoice image → 22 fields | 98.1 · 99.0 · **99.0%** per field | Qwen3.5-2B: 87.3% |

## What I build

- **[FactuSight](https://factusight.com)** (founder): local AI that reads Spanish invoices. Own vision-language models (LoRA on Qwen3.5), a native C++20 inference engine on llama.cpp (CUDA, Vulkan, CPU with automatic fallback), per-field confidence, human review and an encrypted database. No data leaves the machine.
- **On-prem RAG assistant for technical support**: hybrid search (pgvector + full text, RRF fusion), BGE-M3 embeddings, Qwen3 reranker and Qwen3.5-9B answering with cited sources. A C++ daemon with embedded llama.cpp, **continuous batching**, admission control, SSE streaming and its own **MCP server**; personal data (PII) anonymized at ingestion.
- **Local speech AI**: speech-to-speech, speech-to-text and text-to-speech models running on the client's own GPUs, plus VoIP/SIP integration (FreeSWITCH, Asterisk).
- **Agents with tools** over CRM, ERP and email; chatbots and voicebots with handoff to a human; private document automation down to the ERP.
- **30+ freelance projects for 20+ clients** since 2018: local open-weight models, cloud (OpenAI, Claude, Gemini, Azure OpenAI, AWS Bedrock in EU regions) or hybrid.

## Tech stack

**AI / LLM**<br>
![llama.cpp](https://img.shields.io/badge/llama.cpp-GGUF-333?style=flat-square) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) ![Vulkan](https://img.shields.io/badge/Vulkan-AC162C?style=flat-square&logo=vulkan&logoColor=white) ![vLLM](https://img.shields.io/badge/vLLM-SGLang-30A2FF?style=flat-square) ![Unsloth](https://img.shields.io/badge/Unsloth-LoRA_·_SFT_·_DPO-0f766e?style=flat-square) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![MCP](https://img.shields.io/badge/MCP-servers-555?style=flat-square) ![Models](https://img.shields.io/badge/Qwen_·_Gemma_·_Llama-VLMs_·_ASR_·_TTS-6f42c1?style=flat-square)

**Languages & APIs**<br>
![C++20](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Qt](https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC_·_REST_·_WebSockets-244c5a?style=flat-square)

**Infra & data**<br>
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Grafana](https://img.shields.io/badge/Prometheus_·_Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL_·_pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

## How I work

- **Measure everything that matters** (p50/p95 latency, VRAM, cost, quality) and publish the real results, negative ones included.
- **The AI proposes, deterministic code decides** what is critical: command and query verifiers, validation rules, human review of what is uncertain.
- **Architecture decisions written down before building**, with the discarded alternatives and why.
- **Multi-agent development** (Claude Code, Codex): parallel subagents per task, cross-model adversarial review and tests as the acceptance gate.

<p align="center"><sub>Computer Engineering · Universitat Politècnica de València · exchange at Eindhoven University of Technology</sub></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Manuel García Sanz · AI Architect · LLM platforms · On-prem & hybrid AI" src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://manuelgs.com"><img alt="Website" src="https://img.shields.io/badge/manuelgs.com-1f6feb?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjEwIi8%2BPHBhdGggZD0iTTIgMTJoMjBNMTIgMmExNSAxNSAwIDAgMSAwIDIwTTEyIDJhMTUgMTUgMCAwIDAgMCAyMCIvPjwvc3ZnPg%3D%3D"></a>
  <a href="https://www.linkedin.com/in/manuel-garcia-sanz-9555a484/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0xNiA4YTYgNiAwIDAgMSA2IDZ2N2gtNHYtN2EyIDIgMCAwIDAtNCAwdjdoLTR2LTdhNiA2IDAgMCAxIDYtNnoiLz48cmVjdCB4PSIyIiB5PSI5IiB3aWR0aD0iNCIgaGVpZ2h0PSIxMiIvPjxjaXJjbGUgY3g9IjQiIGN5PSI0IiByPSIyIi8%2BPC9zdmc%2B"></a>
  <a href="https://huggingface.co/manuelgscom"><img alt="Hugging Face" src="https://img.shields.io/badge/Hugging_Face-1f2328?style=for-the-badge&logo=huggingface&logoColor=FFD21E"></a>
  <a href="mailto:contacto@manuelgs.com"><img alt="Email" src="https://img.shields.io/badge/contacto@manuelgs.com-8250df?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxyZWN0IHg9IjIiIHk9IjQiIHdpZHRoPSIyMCIgaGVpZ2h0PSIxNiIgcng9IjIiLz48cGF0aCBkPSJtMjIgNi0xMCA3TDIgNiIvPjwvc3ZnPg%3D%3D"></a>
  <a href="https://www.google.com/maps/place/Valencia,+Spain"><img alt="Location" src="https://img.shields.io/badge/Valencia_·_Remote_(CET)-30363d?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0yMCAxMGMwIDYtOCAxMi04IDEycy04LTYtOC0xMmE4IDggMCAwIDEgMTYgMHoiLz48Y2lyY2xlIGN4PSIxMiIgY3k9IjEwIiByPSIzIi8%2BPC9zdmc%2B"></a>
</p>

## About me

Computer Engineer (UPV) with **15 years** building mission-critical, low-latency systems in **C++ and Linux**, most of them in contact-center and VoIP software, where an outage means calls dropping in real time. For six years I was the last escalation level: whatever broke in production (telephony, servers, performance, security) ended up on my desk.

Today I design and ship AI platforms **end to end**: data, fine-tuning, evaluation, optimized GPU inference and operations, on-prem, in the cloud or hybrid. I bring the systems background into it: native inference engines instead of Python glue, capacity and VRAM planning, measured latency, and software that keeps running when the GPU fails.

A hands-on architect: I decide on measured data (latency, cost, quality) and know what to automate, what a person should review and what data must never leave the client. My recurring pattern: **small specialized models that beat generalists 10× their size**, with the critical decisions made by deterministic code.

### Core expertise

- **C++ (expert, 15 years)**: modern C++20, multithreaded low-latency daemons, native single-binary tools for CPU and GPU, llama.cpp embedded as a library (continuous batching, admission control, SSE streaming), Qt, gRPC, REST and WebSockets, Asterisk modules.
- **Linux servers (expert)**: production administration and hardening, performance and scaling bottlenecks, incident response and security incidents on cloud fleets (AWS, OVH), systemd services, Docker, CI/CD.
- **AI platforms**: fine-tuning (full, LoRA, SFT, DPO, distillation), synthetic data, rigorous evaluation (frozen test sets, LLM-as-judge, execution scoring, statistical tests), GGUF quantization, GPU inference with CUDA and Vulkan, RAG, agents and MCP servers.
- **Real-time voice & telephony**: VoIP/SIP, Asterisk, FreeSWITCH; local speech-to-speech, speech-to-text and text-to-speech models.
- **Data**: PostgreSQL and MongoDB at high volume, pgvector, hybrid search, SQLCipher.
- **Leadership**: led teams of 6–15 people (development, systems and support), from analysis to production; the technical face for clients and management.

### Career

| Years | Role |
|---|---|
| 2025&nbsp;–&nbsp;now | **Founder & lead architect**, [FactuSight](https://factusight.com): local AI for invoice automation |
| 2023&nbsp;–&nbsp;now | **Senior Software Engineering Consultant, AI**, contact-center & VoIP software company |
| 2018&nbsp;–&nbsp;now | **Freelance software & AI consultant**: 30+ projects for 20+ clients |
| 2021&nbsp;–&nbsp;2022 | **Lead Backend Developer & Systems Architect**: architecture and coordination of the backend, systems and VoIP teams |
| 2014&nbsp;–&nbsp;2021 | **Technical Lead**: last escalation level for telephony and Linux cloud servers; team of 6–15 people |
| 2011&nbsp;–&nbsp;2014 | **C++ Software Developer**: Qt/C++, Asterisk modules, PostgreSQL and Linux |

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
<a href="https://github.com/ggml-org/llama.cpp"><img alt="llama.cpp · GGUF" src="https://img.shields.io/badge/llama.cpp_%C2%B7_GGUF-333333?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxyZWN0IHg9IjUiIHk9IjUiIHdpZHRoPSIxNCIgaGVpZ2h0PSIxNCIgcng9IjIiLz48cmVjdCB4PSI5IiB5PSI5IiB3aWR0aD0iNiIgaGVpZ2h0PSI2Ii8%2BPHBhdGggZD0iTTkgMnYzTTE1IDJ2M005IDE5djNNMTUgMTl2M00yIDloM00yIDE1aDNNMTkgOWgzTTE5IDE1aDMiLz48L3N2Zz4%3D"></a>
<a href="https://developer.nvidia.com/cuda-toolkit"><img alt="CUDA" src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white"></a>
<a href="https://www.vulkan.org"><img alt="Vulkan" src="https://img.shields.io/badge/Vulkan-AC162C?style=for-the-badge&logo=vulkan&logoColor=white"></a>
<a href="https://github.com/vllm-project/vllm"><img alt="vLLM" src="https://img.shields.io/badge/vLLM-1f6feb?style=for-the-badge&logo=vllm&logoColor=white"></a>
<a href="https://github.com/sgl-project/sglang"><img alt="SGLang" src="https://img.shields.io/badge/SGLang-0b6e99?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxyZWN0IHg9IjIiIHk9IjMiIHdpZHRoPSIyMCIgaGVpZ2h0PSI3IiByeD0iMiIvPjxyZWN0IHg9IjIiIHk9IjE0IiB3aWR0aD0iMjAiIGhlaWdodD0iNyIgcng9IjIiLz48cGF0aCBkPSJNNiA2LjVoLjAxTTYgMTcuNWguMDEiLz48L3N2Zz4%3D"></a>
<a href="https://github.com/unslothai/unsloth"><img alt="Unsloth · LoRA · SFT · DPO" src="https://img.shields.io/badge/Unsloth_%C2%B7_LoRA_%C2%B7_SFT_%C2%B7_DPO-0f766e?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik00IDIxdi03TTQgMTBWM00xMiAyMXYtOU0xMiA4VjNNMjAgMjF2LTVNMjAgMTJWM00xIDE0aDZNOSA4aDZNMTcgMTZoNiIvPjwvc3ZnPg%3D%3D"></a>
<a href="https://huggingface.co/manuelgscom"><img alt="Hugging Face" src="https://img.shields.io/badge/Hugging_Face-1f2328?style=for-the-badge&logo=huggingface&logoColor=FFD21E"></a>
<a href="https://modelcontextprotocol.io"><img alt="MCP" src="https://img.shields.io/badge/MCP-555555?style=for-the-badge&logo=modelcontextprotocol&logoColor=white"></a>
<a href="https://github.com/QwenLM"><img alt="Qwen" src="https://img.shields.io/badge/Qwen-615CED?style=for-the-badge&logo=qwen&logoColor=white"></a>
<a href="https://ai.google.dev/gemma"><img alt="Gemma" src="https://img.shields.io/badge/Gemma-1a73e8?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0xMiAzbDEuOSA1LjZMMTkuNSAxMC41bC01LjYgMS45TDEyIDE4bC0xLjktNS42TDQuNSAxMC41bDUuNi0xLjl6Ii8%2BPHBhdGggZD0iTTE5IDN2NE0xNyA1aDQiLz48L3N2Zz4%3D"></a>
<a href="https://www.llama.com"><img alt="Llama" src="https://img.shields.io/badge/Llama-0467DF?style=for-the-badge&logo=meta&logoColor=white"></a>
<img alt="VLMs · ASR · TTS" src="https://img.shields.io/badge/VLMs_%C2%B7_ASR_%C2%B7_TTS-b3388f?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxyZWN0IHg9IjkiIHk9IjIiIHdpZHRoPSI2IiBoZWlnaHQ9IjEyIiByeD0iMyIvPjxwYXRoIGQ9Ik0xOSAxMHYxYTcgNyAwIDAgMS0xNCAwdi0xTTEyIDE4djRNOCAyMmg4Ii8%2BPC9zdmc%2B">

**Languages & APIs**<br>
<a href="https://isocpp.org"><img alt="C++20" src="https://img.shields.io/badge/C++20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"></a>
<a href="https://www.python.org"><img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"></a>
<a href="https://www.typescriptlang.org"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"></a>
<a href="https://www.qt.io"><img alt="Qt" src="https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white"></a>
<a href="https://grpc.io"><img alt="gRPC" src="https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik00IDEyaDRNMTYgMTJoNE04IDhoOHY4SDh6TTEyIDR2NE0xMiAxNnY0Ii8%2BPC9zdmc%2B"></a>
<img alt="REST · WebSockets" src="https://img.shields.io/badge/REST_%C2%B7_WebSockets-30363d?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik03IDdsLTUgNSA1IDVNMTcgN2w1IDUtNSA1TTE0IDRsLTQgMTYiLz48L3N2Zz4%3D">

**Infra & data**<br>
<a href="https://www.kernel.org"><img alt="Linux" src="https://img.shields.io/badge/Linux-1f2328?style=for-the-badge&logo=linux&logoColor=FCC624"></a>
<a href="https://www.docker.com"><img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"></a>
<a href="https://kubernetes.io"><img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"></a>
<a href="https://aws.amazon.com"><img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0xNy41IDE5SDhhNiA2IDAgMSAxIDUuNy03LjlBNC41IDQuNSAwIDEgMSAxNy41IDE5eiIvPjwvc3ZnPg%3D%3D"></a>
<a href="https://azure.microsoft.com"><img alt="Azure" src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0xNy41IDE5SDhhNiA2IDAgMSAxIDUuNy03LjlBNC41IDQuNSAwIDEgMSAxNy41IDE5eiIvPjwvc3ZnPg%3D%3D"></a>
<a href="https://github.com/features/actions"><img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"></a>
<a href="https://prometheus.io"><img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"></a>
<a href="https://grafana.com"><img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"></a>
<a href="https://www.postgresql.org"><img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"></a>
<a href="https://github.com/pgvector/pgvector"><img alt="pgvector" src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik00IDIwIDE5IDVNMTkgNWgtNk0xOSA1djZNNCAyMGw0LTEyIi8%2BPGNpcmNsZSBjeD0iNCIgY3k9IjIwIiByPSIxLjUiLz48L3N2Zz4%3D"></a>
<a href="https://www.mongodb.com"><img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"></a>

## How I work

- **Measure everything that matters** (p50/p95 latency, VRAM, cost, quality) and publish the real results, negative ones included.
- **The AI proposes, deterministic code decides** what is critical: command and query verifiers, validation rules, human review of what is uncertain.
- **Architecture decisions written down before building**, with the discarded alternatives and why.
- **Multi-agent development** (Claude Code, Codex): parallel subagents per task, cross-model adversarial review and tests as the acceptance gate.

<p align="center"><sub>Computer Engineering · Universitat Politècnica de València · exchange at Eindhoven University of Technology</sub></p>

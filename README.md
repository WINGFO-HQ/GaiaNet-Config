GaiaNet Config for Better Running Nodes
=
## [✅ Qwen1.5-1.8B-Chat (Low VPS) — Minimum Server Requirements](https://github.com/WINGFO-HQ/Gaianet-Config/tree/main/qwen1.5-1.8b-chat_paris)
🖥️ Minimum Server Requirements (CPU-only)
- CPU: 2–4 cores with AVX2 support
- RAM: 4 GB minimum (6–8 GB recommended)
- Disk: ~5 GB free (model + embeddings + snapshot + runtime)
- OS: Linux preferred (Ubuntu 20.04+)
- Network: Required for downloading models and RAG snapshot
```bash
gaianet init --config https://raw.githubusercontent.com/WINGFO-HQ/GaiaNet-Config/refs/heads/main/qwen1.5-1.8b-chat_paris/config.json
```

## [✅ Phi-3 Mini Instruct 4K (Mid VPS) — Minimum Server Requirements](https://github.com/WINGFO-HQ/GaiaNet-Config/tree/main/phi-3-mini-instruct-4k_paris)
- CPU: 4-core (modern x86_64 with AVX2 support)
- RAM: 8 GB (minimum), 16 GB recommended
- Storage: 5–10 GB free (model + snapshot + runtime)
- OS: Linux, macOS, or Windows (with WSL)
- Network: Stable internet for snapshot/model download
- Inference engine: llama.cpp (via GaiaNet integration)
## ✔️ Works well on low-cost VPS or edge devices (like Intel NUC, Raspberry Pi 5 with 8GB+ RAM).
```bash
gaianet init --config https://github.com/WINGFO-HQ/GaiaNet-Config/raw/refs/heads/main/phi-3-mini-instruct-4k_paris/config.json
```

## [✅ Phi-3 Mini Instruct 4K (High VPS) — Minimum Server Requirements](https://github.com/WINGFO-HQ/GaiaNet-Config/tree/main/llama-3-8b-instruct_london)
- CPU: 8-core (modern x86_64 with AVX2 support)
- RAM: 32 GB (absolute minimum), 48–64 GB recommended for responsiveness
- Disk space: 15–20 GB (model + embedding + snapshot + runtime)
- OS: Linux (Ubuntu 20.04+ recommended), macOS also supported
- Network: 10–50 Mbps recommended for model/snapshot pulling and RAG queries
```bash
gaianet init --config https://raw.githubusercontent.com/WINGFO-HQ/GaiaNet-Config/refs/heads/main/llama-3-8b-instruct_london/config.json
```

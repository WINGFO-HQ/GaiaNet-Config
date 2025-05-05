✅ Qwen1.5-1.8B-Chat
=
## 📦 Model Overview
- Model: Qwen1.5-1.8B-Chat-Q5_K_M.gguf
- Parameters: 1.8 billion
- Quantization: Q5_K_M (5-bit, high quality)
- Model Size (Q5_K_M): ~1.1 GB
- Context Length: 4096 tokens
- Prompt Template: chatml (specific to Qwen models)
- Language Support: Primarily English, strong multilingual
- Inference Library: llama.cpp (via llama-edge)

🖥️ Minimum Server Requirements (CPU-only)
=
- CPU: 2–4 cores with AVX2 support
- RAM: 4 GB minimum (6–8 GB recommended)
- Disk: ~5 GB free (model + embeddings + snapshot + runtime)
- OS: Linux preferred (Ubuntu 20.04+)
- Network: Required for downloading models and RAG snapshot

⚡ Recommended Server Specs (for responsive inference)
=
- CPU: 4–8 cores modern x86 (Ryzen 5, i5+)
- RAM: 8–16 GB DDR4
- Disk: SSD/NVMe, 10+ GB free
- GPU: Not required (GGUF is CPU-optimized)
- Threads: 4–8 for efficient parallelism

🧠 Usage Notes
=
- Fast and lightweight model—ideal for low-latency, low-memory environments
- Qwen1.5-1.8B offers high quality chat responses with minimal compute
- Use llama.cpp compiled with BLAS or OpenBLAS for better performance

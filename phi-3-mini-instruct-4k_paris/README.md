✅ Phi-3 Mini Instruct 4K — Server Requirements
=
## 📦 Model Overview
- Model: phi-3-mini-4k-instruct-q5_k_m.gguf
- Parameters: ~3.8 billion
- Quantization: Q5_K_M (5-bit)
- Context length: 4,000 tokens
- Model size: ~1.8–2.2 GB

🖥️ Minimum Server Requirements (CPU-only)
=
- CPU: 4-core (modern x86_64 with AVX2 support)
- RAM: 8 GB (minimum), 16 GB recommended
- Storage: 5–10 GB free (model + snapshot + runtime)
- OS: Linux, macOS, or Windows (with WSL)
- Network: Stable internet for snapshot/model download
- Inference engine: llama.cpp (via GaiaNet integration)
## ✔️ Works well on low-cost VPS or edge devices (like Intel NUC, Raspberry Pi 5 with 8GB+ RAM).

⚡ Recommended for Best Responsiveness
=
- CPU: 6–8 core CPU (e.g., AMD Ryzen 5/7, Intel i5/i7)
- RAM: 16–32 GB
- Optional GPU: Not required, but a small CUDA GPU (e.g., RTX 3050/3060) can help
- SSD: Recommended for faster model loading

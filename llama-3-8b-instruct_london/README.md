✅ LLaMA 3 8B Instruct — Server Requirements
=
## 📦 Model Overview
- Model: Meta-Llama-3-8B-Instruct-Q5_K_M.gguf
- Parameters: 8 billion
- Quantization: Q5_K_M (5-bit)
- Context length: 8192 tokens
- Model size: ~4.5 GB (for Q5_K_M quantization)
- Embedding: Nomic v1.5 (16-bit float, ~800MB)
- RAG snapshot: ~1.2 GB (London tour data)

🖥️ Minimum Server Requirements (CPU-only)
=
- CPU: 8-core (modern x86_64 with AVX2 support)
- RAM: 32 GB (absolute minimum), 48–64 GB recommended for responsiveness
- Disk space: 15–20 GB (model + embedding + snapshot + runtime)
- OS: Linux (Ubuntu 20.04+ recommended), macOS also supported
- Network: 10–50 Mbps recommended for model/snapshot pulling and RAG queries

⚡ Recommended Specs for Optimal Performance
=
- CPU: 12–16 cores (e.g., AMD Ryzen 9, Intel i9)
- Threads: 8–16 inference threads
- RAM: 4 GB DDR4/DDR5
- Disk: NVMe SSD, 20 GB+ free
- GPU: (Optional)	Not used in GGUF, but can offload embedding (if desired)


🧠 Model Architecture Notes
=
- Q5_K_M quantization strikes a good balance between speed and quality
- Model is used for RAG (retrieval-augmented generation) over London tour data
- Context and batch sizes (8192) are already optimal for this model

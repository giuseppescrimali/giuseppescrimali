# Hi, I'm Giuseppe 👋

I am an AI Engineer working at the intersection of engineering and AI/ML. This profile collects my work in GPU computing, deep learning, and LLM/Vision-LLM benchmarking.

📄 [LinkedIn](#) · 📍 Turin, Italy

---

## 🚀 Projects

### [🧠 Unanswerable Question Detection in Document VQA](https://github.com/giuseppescrimali/docvqa-unanswerable-detection)
Can small Vision-LLMs tell when a document question *can't* be answered — by actually reading the document, not guessing? Built a synthetic corruption benchmark on DocVQA (entity/element/layout corruptions), evaluated 3 small Vision-LLMs (2B–4B), and tested 3 in-context mitigation strategies across single- and multi-page settings.
**Highlight:** the smallest model (2B) beat both larger ones — scale wasn't the advantage here.
`Vision-LLMs` `Qwen2-VL` `Gemma-3` `Phi-3.5-Vision` `spaCy` `LLM-as-a-judge`

### [🗄️ Text-to-SQL Benchmarking](https://github.com/giuseppescrimali/text-to-sql-benchmark)
Benchmarked proprietary LLMs (GPT, Gemini, Codestral) against open-weight models (Qwen 4B/8B, Phi-4-mini-reasoning) on natural-language-to-SQL generation, graded across a taxonomy of 7 SQL difficulty patterns and 4 database schemas — including full reasoning-trace evaluation, not just final-answer accuracy.
`Text-to-SQL` `LLM Evaluation` `Prompt Engineering` `Reasoning Analysis`

### [🦠 Malware Detection from API Call Sequences](https://github.com/giuseppescrimali/malware-detection-api-sequences)
Malware vs. benign classification from Windows API-call sequences, comparing a Bag-of-Words + Random Forest baseline, an embedding-based FFNN, and an LSTM (PyTorch).
**Highlight:** the frequency-only baseline outperformed both sequential/neural models on macro F1 — model complexity should match the actual signal in the data, not just what's fashionable.
`PyTorch` `Scikit-learn` `LSTM` `Embeddings` `Imbalanced Classification`

### [⚡ GPU Computing with CUDA](https://github.com/giuseppescrimali/cuda-gpu-optimization)
Hands-on GPU performance work: NumPy → CuPy → custom CUDA kernels (Numba), then profiling and tuning with NVIDIA Nsight Systems — block-size sweeps, parallel reductions, and diagnosing synchronization anti-patterns directly from the profiler timeline.
`CUDA` `Numba` `CuPy` `Nsight Systems` `GPU Profiling`

### [🎓 SysML v2 – Interoperability Tank Model](https://github.com/giuseppescrimali/SysMLv2-Interoperability-TankModel)
My Master's thesis: evaluating the new SysML v2 language for Model-Based Systems Engineering in aerospace, with a liquid hydrogen tank case study and Simulink interoperability — in collaboration with **Leonardo S.p.A.**
`SysML v2` `MBSE` `Simulink` `Systems Engineering`

---

## 🛠️ Tech I work with

**AI/ML:** PyTorch · Scikit-learn · Transformers (Qwen, Gemma, Phi) · Prompt Engineering
**GPU/Performance:** CUDA · Numba · CuPy · NVIDIA Nsight Systems
**Engineering tools:** MATLAB · SolidWorks · Siemens NX · SysML v2 · Simulink
**Languages:** Python · SQL

---

⭐ Feel free to explore the repos above — each has its own README with methodology and key results.

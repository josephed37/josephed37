# Joseph Edjeani

**AI / ML Engineer** · Takoradi, Ghana · Open to remote and relocation

I build machine learning systems end to end: training and evaluating the model, serving it behind a fast API, and shipping it to the cloud with CI/CD. My background is in Electrical & Electronics Engineering, and I'm heading toward robotics and applied AI.

**Main stack:** Python · Go · Rust · PyTorch / TensorFlow · ONNX · LangChain / LangGraph · Docker · GCP

---

## Featured work

### [MammoScan AI](https://github.com/josephed37/mammoscan-AI)
Breast cancer classification from mammograms, built as a full production system rather than a notebook.
- CNN and transfer-learning models in TensorFlow, exported to **ONNX** and served by a **Go** API
- Deployed on **Google Cloud Run**, with the model in GCS and GitHub Actions deploying through **Workload Identity Federation** (no stored keys)
- Data versioned with **DVC**; architecture, deployment and training are documented in `docs/`

### [FactCheck-AI](https://github.com/josephed37/FactCheck-AI)
Fact-checking app that grounds an LLM in live web search.
- **Go** backend pulls fresh results from Tavily, builds the prompt context and calls Gemini
- Shows the sources behind every verdict and keeps a history of checks in SQLite
- Streamlit frontend; the whole stack runs with Docker Compose

### [Dino Vision](https://github.com/josephed37/dino-vision)
The Chrome dinosaur game rebuilt in Pygame and played with hand gestures, using OpenCV for real-time control.

---

## What I'm focused on

- LLM systems that are measured, not just demoed: evaluations, cost and latency tracking, reliability
- Infrastructure for AI in Go and Rust
- Robotics and AI planning

---

## Contact

[LinkedIn](https://www.linkedin.com/in/joseph-edjeani)

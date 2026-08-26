# W2D2 & W2D3: LLM Serving Stack & Docker Containerization

This repository contains the implementation for wrapping the **Qwen/Qwen2.5-0.5B-Instruct** model behind an OpenAI-compatible FastAPI service (W2D2) and containerizing it for production using Docker (W2D3).

## 🚀 Overview
- **FastAPI Backend (`/v1/chat/completions`, `/v1/models`, `/health`)**: Exposes the model under a standard OpenAI-compatible schema contract.
- **Docker Integration**: Containerized environment for robust deployment.

---
<img width="2560" height="484" alt="Screenshot 2026-08-27 004059" src="https://github.com/user-attachments/assets/b152ff73-8caf-4f0d-952b-e3de60f5f2f5" />

Here is the successful test run using the standard OpenAI client pointing to the local FastAPI server:


---

## 🛠️ Getting Started Locally

1. **Create and activate the virtual environment:**
   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate

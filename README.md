# W2D2: LLM Serving Stack

This repository contains the implementation for wrapping the **Qwen/Qwen2.5-0.5B-Instruct** model behind an OpenAI-compatible FastAPI service.

## 🚀 Overview
- **FastAPI Backend (`/v1/chat/completions`, `/v1/models`, `/health`)**: Exposes the model under a standard OpenAI-compatible schema contract.

---

<img width="2560" height="484" alt="Screenshot 2026-08-27 004059" src="https://github.com/user-attachments/assets/af0d4d24-bfa7-4b15-8f49-75567f293632" />


---

## 🛠️ Getting Started Locally



1. **Create and activate the virtual environment:**
   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate
Install dependencies:

PowerShell
pip install -r requirements.txt
Run the FastAPI server:

PowerShell
uvicorn main:app --host 0.0.0.0 --port 8000
Run the client test:

PowerShell
python client_test.py

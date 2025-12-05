# MABE Phase 2: ViT + Attention Maps + Ollama

This is the enhanced **Multimodal AI-Based Explainer (MABE)**.
- Classifies images using a **Vision Transformer (ViT)**.
- Visualizes model focus with **Attention Maps**.
- Explains decisions using **Ollama (Llama 3)**.

## Quickstart

```bash
# Navigate to the MABE directory
cd MABE

# Create and activate virtual environment
python -m venv .venv
# Windows:
.\.venv\Scripts\Activate
# Mac/Linux:
# source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

### Configuration
- `OLLAMA_KEY` and `OLLAMA_URL` are configured in `main.py`.
- Ensure you have Ollama running locally if required by the custom logic, or rely on the configured API key if using a remote proxy.

## Files
- `main.py` — FastAPI backend, ViT inference, Ollama integration.
- `static/` — Frontend (HTML/CSS/JS).
- `requirements.txt` — Python dependencies.



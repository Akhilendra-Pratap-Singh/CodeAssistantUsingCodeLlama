
# 🤖 CodeGuru – Local Code Assistant with Gradio + Ollama

**CodeGuru** is a local, privacy-friendly code assistant built using [Gradio](https://www.gradio.app/) for the frontend and [Ollama](https://ollama.com) with the `CodeLlama` model as the backend. It helps answer coding questions, explain concepts, and generate code — all without sending your data to the cloud.

---

## 🚀 Features

- Uses `CodeLlama` locally via Ollama
- System prompt customization via `Modelfile`
- Simple Gradio-based UI
- Remembers conversation context
- No internet required once models are downloaded

---

## 📁 Project Structure

CodeGuru

1.app.py # Main Python app using Gradio + requests
2. Modelfile # Model configuration for Ollama
3. requirements.txt # Python dependencies
4. README.md # You're here!

## 🔧 Requirements

- Python 3.8+
- [Ollama](https://ollama.com/download) (installed locally)
- RAM: 8–16 GB+ recommended (especially for 7B models)

Install dependencies:
```bash
pip install -r requirements.txt

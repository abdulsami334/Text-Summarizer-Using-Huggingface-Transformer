# 🤖 AI Dialogue Summarizer (T5-Transformer)

An end-to-end Text Summarization system leveraging the **T5 (Text-to-Text Transfer Transformer)** architecture to condense long-form dialogues into concise, context-aware summaries. This project integrates a deep learning backend with a high-performance REST API.

## ✨ Key Features
* **Transformer-Based:** Utilizes Hugging Face's T5 model for high-quality sequence-to-sequence generation.
* **Production-Ready API:** Built with **FastAPI** for high-performance, asynchronous inference.
* **Hardware Acceleration:** Integrated support for **CUDA**, **MPS (Apple Silicon)**, and **CPU** to ensure optimal performance across environments.
* **Optimized Inference:** Implements **Beam Search decoding** ($num\_beams=4$) and early stopping for refined text generation.
* **Custom Preprocessing:** A regex-based pipeline to clean noise (HTML tags, extra whitespace) from raw dialogue data.

## 🛠️ Tech Stack
* **Language:** Python
* **AI/ML:** PyTorch, Hugging Face Transformers
* **Backend:** FastAPI, Uvicorn, Pydantic
* **Frontend:** HTML5, CSS3, JavaScript (Fetch API)

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/t5-dialogue-summarizer.git](https://github.com/your-username/t5-dialogue-summarizer.git)
cd t5-dialogue-summarizer

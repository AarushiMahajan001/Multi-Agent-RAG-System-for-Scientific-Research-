# 🔬 Multi-Agent RAG Research Assistant

An interactive research assistant built using **LangGraph**, **FAISS**, and **Together.ai’s LLaMA-4**. It supports hybrid inputs (PDFs + search queries), modular agent pipelines, and customizable summarization instructions via a **Gradio UI**.

---

## 💡 Features

- 📄 Upload research papers in PDF format
- 🔍 Use SerpAPI to search live web content
- 🧠 Modular agents: Search → PDF → Embed → Retrieve → Summarize
- 🦙 Powered by Together.ai’s LLaMA-4 Maverick model
- 🎛️ Custom summarization instructions like:  
  *“Give me a 1000-word summary with section headers”*

---

## 🧪 Stack

| Component     | Tool                            |
|---------------|---------------------------------|
| LLM           | [Together.ai - LLaMA-4](https://platform.together.xyz/) |
| Vector Store  | FAISS (IVF indexing)            |
| Agents        | LangGraph                       |
| Embeddings    | MiniLM (HuggingFace)            |
| UI            | Gradio                          |
| Search        | SerpAPI                         |

---

## 🚀 Run in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10e2_DUxI7GGY2q5GGnnXfqcOo01ZO9ZV?usp=sharing)

---

## 🧠 Example Prompts

- *Summarize this PDF in 500 words focusing on experimental results.*
- *What are the most cited NAS techniques in 2024? Give bullet points.*
- *What are the recent trends in Gen-AI?.*
- ![image](https://github.com/user-attachments/assets/152b91b2-2014-4518-b145-d10fad8ed750)


---

## 🔐 API Keys Required

Create a `.env` file or input them in the Gradio UI:

```env
SERPAPI_KEY=your-serpapi-key
TOGETHER_API_KEY=your-together-key

---

## 📦 Installation (if running locally)

pip install -r requirements.txt


# Book Recommender

This is an **LLM-powered book recommendation system** that uses vector search, zero-shot classification, and sentiment analysis to suggest books based on descriptions. The project processes text data, builds vector embeddings, and provides an interactive Gradio dashboard for recommendations.

---

## Tech Stack

* **LangChain** – Text splitting and vector database integration
* **Hugging Face Transformers** – Zero-shot classification and sentiment analysis models
* **Chroma / FAISS** – Vector database for semantic search
* **Gradio** – Interactive dashboard UI
* **PyCharm** – Development environment

---

## Features

* **Vector Search** – Finds similar books using embeddings and semantic similarity
* **Zero-Shot Classification** – Categorizes book descriptions without fine-tuning
* **Sentiment Analysis** – Extracts emotions and sentiment from book descriptions
* **Interactive Dashboard** – Gradio-based UI for easy book recommendations
* **Data Cleaning** – Handles missing data, short descriptions, and text preprocessing

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Madhusanka-slc/book-recommender.git
cd book-recommender
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Gradio dashboard:

```bash
python gradio-dashboard.py
```

Now the dashboard will be available at `http://127.0.0.1:7860`. You can enter book descriptions or queries to get personalized recommendations.

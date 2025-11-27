# Local RAG Assistant 

This project demonstrates a lightweight **Retrieval-Augmented Generation (RAG)** assistant built entirely in **Jupyter Notebook** using:

- **HuggingFace sentence-transformers embeddings** (offline/local)
- **ChromaDB** (persistent local vector storage)
- **nltk** for text chunking
- Optional local LLM fallback (transformers)

### 🚀 Features
- Ingest custom lesson text files from `data/`
- Split into overlapping chunks and embed into Chroma vector DB
- Retrieve top-K similar chunks for a query
- Answer questions based only on retrieved context
- Logs demo Q&A to `output_demo.txt` for publication / GitHub record

### 🛠 Setup (for beginners)

1. Install all dependencies:
   ```python
   pip install -r requirements.txt

# Multimodal Retrieval-Augmented Generation (RAG)

This project corresponds to **Part I** of the report `Lab2_Report_Team15 (2).pdf`.

## Project summary (from report)

This system answers macroeconomics questions grounded in a PDF textbook using a multimodal RAG pipeline that combines:

- **BGE-large** text embeddings
- **CLIP** visual embeddings for figures/tables
- **ChromaDB** vector storage
- **BM25** re-ranking
- **Claude Sonnet** for final answer generation

Reported outcome: **Kaggle score = 0.366**.

## Repository contents

- `rag_best.ipynb` - Main notebook implementing the pipeline.
- `submission (4).csv` - Generated submission file.

## Run

1. Open `rag_best.ipynb` in Jupyter/Colab.
2. Install dependencies used in the notebook.
3. Run all cells to reproduce outputs.

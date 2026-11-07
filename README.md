# Eswatini IMF 2025–2026 – LLM Financial Analysis

**Dataset:** IMF Country Report No. 26/260 (2026)

## Project Overview
This project analyses Eswatini's IMF Country Report using local Large Language Models (LLMs). It focuses on financial information extraction, summarisation, economic trends, financial stability risks and data visualisation.

## Models Used
- **IBM Granite 3.3 8B Instruct:** Document summarisation and financial data extraction.
- **Mistral 7B Instruct v0.3:** Evaluation of summaries, financial indicators and RAG responses.
- **BAAI/bge-small-en-v1.5:** Text embeddings for FAISS-based retrieval.

## Tools and Libraries
Python, Google Colab, PyTorch, Transformers, Sentence-Transformers, FAISS, Pandas, Matplotlib and pypdf.

## Project Outputs
- 9 section summaries and an executive summary
- 6 financial indicators in JSON format
- 7 financial theme distributions
- 6 economic strengths and 6 vulnerabilities
- 4 economic trend series (2023–2031)
- FAISS-based RAG with 4 question-answer evaluations
- 19 LLM evaluations
- High-resolution four-panel financial dashboard

## How to Run
1. Open the notebook in Google Colab.
2. Select an **A100 GPU** runtime.
3. Upload the Eswatini IMF 2026 PDF.
4. Run all notebook cells sequentially.
5. Access the generated outputs in the `eswatini_outputs` folder.

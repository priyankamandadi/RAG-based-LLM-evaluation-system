# RAG Based LLM Evaluation System

A Retrieval-Augmented Generation (RAG) evaluation framework for assessing LLM performance across multiple domains using the RAGBench and RGB benchmarks.

## Features
- Multi-domain RAG evaluation
- Hybrid retrieval (BM25 + FAISS)
- Cross-encoder reranking
- FAISS vector indexing
- Evaluation of faithfulness, relevance, completeness and robustness
- Support for multiple LLM backends

## Tech Stack
Python, LangChain, FAISS, Hugging Face Transformers, Sentence Transformers, BM25, Qwen/Llama compatible models.

## Project Structure
- Three Jupyter notebooks implementing the complete evaluation workflow.
- Datasets, embeddings and FAISS indices as required by the notebooks.

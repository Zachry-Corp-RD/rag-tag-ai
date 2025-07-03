# rag-tag-ai

**RAG TAG blog series -** Each post will unpack technical components of RAG using practical tutorials—culminating in a showcase of applied AI for capital project delivery, jobsite knowledge retrieval, and safety insights.

This repository takes a clear, hands-on approach to **Retrieval-Augmented Generation (RAG)**, breaking down advanced techniques into straightforward, understandable implementations. Instead of relying on frameworks like `LangChain` or `FAISS`, everything here is built using familiar Python libraries `openai`, `numpy`, `matplotlib`, and a few others.

## Overview

This repository demonstrates a minimal implementation of a Retrieval-Augmented Generation (RAG) workflow using:

- PyMuPDF (fitz) for text extraction
- NumPy for basic vector math
- JSON for data storage

## Usage

Run the notebook `01_simple_rag.ipynb` in GitHub Codespaces or locally.

## Requirements

- Python 3.10
- Dependencies listed in `requirements.txt` or `environment.yml`

The repository follows a hands-on educational approach with three core principles:

| Principle                    | Implementation                                                          | Purpose                       |
| ---------------------------- | ----------------------------------------------------------------------- | ----------------------------- |
| **Framework-Free**           | Uses `mistral`, `numpy`, `matplotlib` instead of `LangChain` or `FAISS` | Exposes underlying mechanisms |
| **From-Scratch Building**    | Custom `SimpleVectorStore` class, manual chunking logic                 | Demonstrates core concepts    |
| **Self-Contained Notebooks** | Each `.ipynb` file runs independently                                   | Enables focused learning      |

Each notebook follows a consistent structure: technique explanation, step-by-step implementation, code examples with inline comments, evaluations with comparisons, and result visualizations.

This blog series helps demystify RAG and makes it easier to understand how it really works, by focusing on the fundamentals and frameworks.

## 🎯 Why This Series?

Building on insights from our earlier [CII blog post announcing the AI Initiative](https://www.construction-institute.org/blog/announcing-a-cii-ai-initiative), this series continues the conversation with a hands-on, music-inspired approach to Retrieval-Augmented Generation (RAG).

As the CII Annual Conference approaches in the heart of **Music City, Nashville**, this series will orchestrate a practical, code-first look at building AI assistants that **don’t hallucinate**—they _retrieve, harmonize, and respond_ based on verified project knowledge.

Each post breaks down one “movement” of the RAG framework with hands-on tutorials and real construction data examples—from safety manuals to equipment specs.

## 🎵 The Playlist


| Notebook                                      | Description                                                                                                                                                         |
| :-------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [1. Simple RAG](01_simple_rag.ipynb)           | "The Overture" - Basic RAG                                                                                                       |
| [2. Semantic Chunking](02_semantic_chunking.ipynb) | "Finding the Right Tempo" - Chunking strategies                                                                                           |
| [3. Harmonizing Search Vectors](03_harmonizing_search_vectors.ipynb) | "Harmonizing Search" - Hybrid approaches and vectors.                                                                                    |
| [4. Context Enriched RAG](04_context_enriched_rag.ipynb) | "Orchestrating Context" - Advanced retrieval Retrieves neighboring chunks to provide more context.                                                                                                     |
| [5. Tuning for Performance](05_evaluation_framework.ipynb) | "Tuning for Performance" - Evaluation Framework                                                                                               |
| [6. Document Augmentation RAG](06_construction_use_cases.ipynb) | "The Construction Symphony" - Real construction scenarios                                                                                           |


📅 Weekly Release Timeline (Adjusted Start)

  

|      |          |                                         |
| ---- | -------- | --------------------------------------- |
| Posts | Date     | Topic                                   |
| 1    | July 7   | "The Overture" - Basic RAG         |
| 2    | July 10  | "Finding the Right Tempo" - Chunking strategies|
| 3    | July 17  |"Harmonizing Search" - Hybrid approaches      |
| 4    | July 24  | "Orchestrating Context" - Advanced retrieval |
| 5    | July 31  | "Tuning for Performance" - Evaluation   |
| 6    | August 7 |  "The Construction Symphony" - Real applications |
  


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
| [1. Simple RAG](01_simple_rag.ipynb)           | A basic RAG implementation.  A great starting point!                                                                                                       |
| [2. Semantic Chunking](02_semantic_chunking.ipynb) | Splits text based on semantic similarity for more meaningful chunks.                                                                                           |
| [3. Chunk Size Selector](03_chunk_size_selector.ipynb) | Explores the impact of different chunk sizes on retrieval performance.                                                                                    |
| [4. Context Enriched RAG](04_context_enriched_rag.ipynb) | Retrieves neighboring chunks to provide more context.                                                                                                     |
| [5. Contextual Chunk Headers](05_contextual_chunk_headers_rag.ipynb) | Prepends descriptive headers to each chunk before embedding.                                                                                                |
| [6. Document Augmentation RAG](06_doc_augmentation_rag.ipynb) | Generates questions from text chunks to augment the retrieval process.                                                                                           |


📅 Weekly Release Timeline (Adjusted Start)

  

|      |          |                                         |
| ---- | -------- | --------------------------------------- |
| Week | Date     | Topic                                   |
| 1    | July 3   | Intro to RAG & Simple Pipeline          |
| 2    | July 10  | Semantic Chunking + Embedding           |
| 3    | July 17  | Context-Enriched Retrieval              |
| 4    | July 24  | Prompt Engineering + Guardrails         |
| 5    | July 31  | RAG for Construction Use Cases          |
| 6    | August 7 | Post-Conference Wrap-Up + Future Vision |
  


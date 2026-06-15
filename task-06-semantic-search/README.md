# Task 06: Enterprise Semantic Search Engine

## Implementation Summary
This folder contains the complete pipeline for CoreTech Innovation's semantic search module, comparing dense vector space search against traditional keyword retrieval.

### Benchmarking Matrix (Traditional vs Semantic)

| Feature Evaluation | Traditional Keyword Search (TF-IDF) | Advanced Semantic Search (Dense Space) |
| :--- | :--- | :--- |
| **Matching Algorithm** | Exact word token matching (Lexical). | Synonyms, intent, and conceptual context mapping. |
| **Model Architecture** | Sparse matrices tracking keyword distributions. | `all-MiniLM-L6-v2` Sentence-Transformers (384 Dimensions). |
| **Out-of-Vocabulary handling**| Fails entirely if the exact query word doesn't exist. | Excellent; resolves semantic meanings effortlessly. |
| **Core AI Application** | Basic text tagging and inverted indexing. | Multi-turn chatbots, dynamic knowledge base retrieval (RAG). |

## Deliverables
* **Main Notebook:** `coretech_semantic_search.ipynb` (Fully executed with outputs committed).

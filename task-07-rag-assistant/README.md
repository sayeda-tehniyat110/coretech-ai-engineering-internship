# Task 07: RAG-Style Knowledge Assistant System

## Task Objective
Designed and deployed a Retrieval-Augmented Generation (RAG) assistant pipeline for CoreTech Innovation. The architecture ingests raw text documents, converts them into dense vector embeddings using `all-MiniLM-L6-v2`, and maps user queries to the most relevant internal records to synthesize context-insulated responses.

---

## Document Matrix Architecture

| Source Document Name | Core Knowledge Assets Tracked |
| :--- | :--- |
| **Company Profile** | Academic engineering background, mission statement, regional footprint. |
| **Services** | AI automation pipelines, Full-Stack Web, UI/UX prototyping, visual branding. |
| **Project Process** | 4-Phase corporate project lifecycles and GitHub sprint transparency. |
| **Pricing Sample** | Dynamic pricing metrics, $1500 baseline setups, full source code ownership. |
| **FAQs** | Code repository management, legacy database migrations, milestone delivery tracking. |

## System Features Deployed
* **Semantic Mapping:** Leverages vector alignments instead of exact word matches.
* **Source Citations:** Explicitly references which knowledge base document was processed.
* **Fallback Boundaries:** Includes confidence checking to handle out-of-scope inquiries safely.

## Deliverables
* **Main Notebook File:** `coretech_rag_assistant.ipynb` (Committed with verified test outputs).

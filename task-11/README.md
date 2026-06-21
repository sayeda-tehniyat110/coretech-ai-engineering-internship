# Task 11: Production RAG Knowledge Assistant

## Project Overview
This folder houses the complete working capstone architecture for CoreTech Innovation's corporate retrieval engine. The system automates corporate document lookup by transforming flat structural records into 384-dimensional mathematical vector slots via an `all-MiniLM-L6-v2` Sentence-Transformer pipeline, executing contextual generation algorithms via an ongoing terminal shell.

---

## Technical Specifications Matrix

| System Component | Engineering Stack Parameters | Function Description |
| :--- | :--- | :--- |
| **Data Repository** | `coretech_capstone_knowledge_base.csv` | Tracks 5 corporate documents detailing profiles, schedules, pricing configurations, and processes. |
| **Embedding Vectorizer**| Sentence-Transformers `all-MiniLM-L6-v2` | Maps unstructured text patterns into dense float arrays capturing synonym intents. |
| **Alignment Logic** | PyTorch Cosine Similarity Matching | Measures angular vector boundaries between client tokens and indexed data fields. |
| **Runtime Interface** | Python `while True` Shell Loop | Maintains persistent terminal context processing inquiries until explicit termination rules. |

## Knowledge Base Architecture Maps Included
* **Company Profile:** Details computer systems engineering roots, regional footprint (Sindh, Pakistan), and mission logic.
* **Services Portfolio:** Outlines AI pipelines, Full-Stack Web tracking (PHP/SQL components), UI/UX wireframes, and branding assets.
* **Engineering Process:** Manages 4-Phase project lifecycles from initial scoping documentation to complete source code git handovers.
* **Pricing Framework:** Logs sample investment setups ($1,500 baseline bounds), dynamic parameters, and explicit code ownership mappings.
* **Operational FAQs:** Resolves support queries, git audit paths, and runtime deployment queries.

## Project Deliverables
* **Capstone Notebook:** `coretech_capstone_rag.ipynb` (Fully structured, verified script loops).
* **Database Component:** `coretech_capstone_knowledge_base.csv` (Flat internal knowledge database logs).

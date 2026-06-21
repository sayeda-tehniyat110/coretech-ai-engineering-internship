# Task 04: CoreTech Client Onboarding Rule-Based Chatbot Engine

## Project Overview
Designed and developed a production-ready python rule-based customer onboarding assistant framework for CoreTech Innovation (Sindh, Pakistan). The pipeline dynamically reads user queries, parses string structures against core client intents, maps them to an underlying flat knowledge base containing verified structural responses, handles out-of-vocabulary edge-cases, and maintains an active session loop.

---

## Technical Features Matrix

| System Vector | Engineering Specification Parameters | Functional Description |
| :--- | :--- | :--- |
| **Data Repository** | `coretech_faq.csv` | A collection of 25 structured FAQs wrapped around double quotes to preserve string integrity and commas. |
| **Parsing Engine** | Intent-Keyword Mapping | Evaluates targeted intent checks across multi-word variations to match base strings smoothly. |
| **Fallback Strategy** | Tokenized Match Backup | Scans individual question word structures as a secondary routing mechanism for semantic variations. |
| **Runtime Session** | Interactive `while True` Loop | Provides persistent user shell interface routing questions until explicit termination commands. |

## Targeted Knowledge Domains Included
1. **Core Agency Profiles:** Details our background in computer systems engineering, microprocessor architecture, and backend logic systems.
2. **Services Portfolio:** Maps engineering tracks across Full-Stack Web Development (PHP/SQL), AI Automations, and Figma UI/UX prototyping.
3. **Financial Matrices:** Explains dynamic project pricing calculations and standard baseline startups packages starting at $1,500 USD.
4. **Agile Operational Protocols:** Validates source code IP ownership, active repository audit access via GitHub, and technical warranties.

## Assets Inside This Directory
* **Jupyter Notebook:** `coretech_faq_chatbot.ipynb` (Contains the compiled runtime chatbot system execution).
* **Flat Data Sheet:** `coretech_faq.csv` (The underlying 25-row structural enterprise knowledge repository).

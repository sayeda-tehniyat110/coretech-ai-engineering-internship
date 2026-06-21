# Task 10: End-to-End AI Automation Workflow Pipeline

## Task Objective
Designed and engineered a fully automated corporate inquiry workflow pipeline for CoreTech Innovation. The automated pipeline ingests raw text messages, extracts discrete entity attributes (Client details, budgets, and operational targets), models structural priorities, synthesizes client notification outputs, and logs transaction audits directly into flat data files.

---

## Architectural Workflow Stages
1. **Message Ingestion Model:** Receives and loops through incoming raw ticket inputs.
2. **Regex Attribute Parsing:** Extracts target parameters (`Client Name`, `Email`, and `Budget`) dynamically via pattern recognition constraints.
3. **Priority Triage Matrix:** Ranks project urgencies based on resource constraints and budget thresholds.
4. **Contextual Reply Generation:** Formats customized business communications utilizing isolated target parameters.
5. **Database Storage Logging:** Flattens transactional arrays and appends runtime records to `coretech_automation_logs.csv`.

## Deliverables inside this Folder
* **Jupyter Notebook:** `coretech_automation_workflow.ipynb` (Fully compiled processing script logs).
* **Logging Matrix Data:** `coretech_automation_logs.csv` (Flat file database storing all processed inquiries).

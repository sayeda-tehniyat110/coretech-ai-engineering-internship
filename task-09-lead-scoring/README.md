# Task 09: Algorithmic Lead Scoring & Service Routing Engine

## Task Objective
Designed and engineered a corporate lead scoring and service mapping pipeline for CoreTech Innovation. The architecture processes unstructured inbound client profiles, assigns a standardized 0-100 algorithmic score based on complex business metrics, flags categorical prioritization tiers, and generates tailored engineering implementations.

---

## Technical Weight Allocation Architecture

| Attribute Vector | Max Point Weight | Real-World System Validation Criteria |
| :--- | :--- | :--- |
| **Budget Signals** | 35 Points | Continuous value distribution scaled to capture premium projects ($15,000 max). |
| **Urgency & Timeline**| 25 Points | Prioritizes operational timelines logging 'Immediate' launch requirements. |
| **Company Size** | 15 Points | Enterprise and Corporate metrics score higher base points vs early startups. |
| **Engagement Level** | 15 Points | New parameters logging interactions ('High Engagement' / 'Passive' / 'Cold Outbound'). |
| **Acquisition Source**| 10 Points | High tier scores are given to direct inbound website structures and client referrals. |

## Automation Triage Strategy
* **High Priority (Score >= 70):** Immediate account sync, auto-routed to senior project managers.
* **Medium Priority (Score 45-69):** Enters email onboarding funnel with template technical proposals attached.
* **Low Priority (Score < 45):** Logged in CRM registries for generic marketing newsletters.

## Production Assets inside this Directory
* **Jupyter Notebook:** `coretech_lead_scoring.ipynb` (Fully compiled engineering calculation scripts).
* **Source Dataset:** `coretech_leads.csv` (50 unstructured raw sample profiles containing engagement dimensions).
* **Computed Output Database:** `coretech_scored_leads.csv` (Final analytic matrix sheets).

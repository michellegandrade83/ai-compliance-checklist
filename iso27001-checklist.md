# ISO/IEC 27001 — AI Security Compliance Checklist

**Framework:** ISO/IEC 27001:2022 — Information Security Management Systems  
**Applicable to:** Organizations using AI systems that process, store, or transmit sensitive information

---

## How to Use
Apply these controls specifically to your AI systems and the data they handle.

| # | Control | ISO 27001 Domain | Status | Notes |
|---|---|---|---|---|
| 1 | AI system assets are inventoried and classified | A.5.9 — Asset Management | ☐ | |
| 2 | Data processed by AI is classified by sensitivity | A.5.12 — Information Classification | ☐ | |
| 3 | Access to AI systems is restricted by role | A.8.2 — Privileged Access Rights | ☐ | |
| 4 | Authentication controls are applied to AI interfaces | A.8.5 — Secure Authentication | ☐ | |
| 5 | AI training data is protected from unauthorized access | A.8.10 — Information Deletion | ☐ | |
| 6 | AI system changes follow a change management process | A.8.32 — Change Management | ☐ | |
| 7 | AI suppliers and vendors are assessed for security | A.5.19 — Supplier Relationships | ☐ | |
| 8 | Contracts with AI vendors include security requirements | A.5.20 — Supplier Agreements | ☐ | |
| 9 | AI-related incidents are logged and investigated | A.5.25 — Incident Management | ☐ | |
| 10 | Business continuity plan covers AI system failures | A.5.29 — Business Continuity | ☐ | |
| 11 | Compliance with legal/regulatory requirements is verified | A.5.31 — Legal Requirements | ☐ | |
| 12 | AI system logs are protected and retained | A.8.15 — Logging | ☐ | |
| 13 | Vulnerability management covers AI components | A.8.8 — Vulnerability Management | ☐ | |
| 14 | Staff handling AI systems receive security training | A.6.3 — Awareness and Training | ☐ | |

---

## Notes for AI-Specific Application

- **A.5.19 & A.5.20** are especially critical for organizations using third-party AI tools (e.g., OpenAI, Anthropic). Ensure contracts define data handling, retention, and breach notification obligations.
- **A.8.32** applies when updating AI models or retraining on new data — treat model updates as system changes.
- **A.5.12** — AI systems often process multiple data categories simultaneously. Classification should cover all data types in the pipeline.

---

## References
- ISO/IEC 27001:2022 standard: https://www.iso.org/standard/82875.html
- ISO/IEC 42001 (AI Management Systems): https://www.iso.org/standard/81230.html

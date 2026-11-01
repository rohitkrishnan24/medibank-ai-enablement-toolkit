# Enterprise AI Enablement Toolkit for Microsoft 365 Copilot

**RMIT University · COSC2667/2777 · Project P000280DS**  
**Industry Partner:** Medibank Private  
**Industry Supervisor:** Avishek Mitra · avishek.mitra@medibank.com.au  
**Academic Supervisor:** Dr. Xiang Li · xiang.li2@rmit.edu.au  

---

## Team

| Name | Student ID | Workstream |
|---|---|---|
| Rohit Krishnan | S4116077 | Excel Copilot Skill Library |
| Ngoc Anh Thu Nguyen | — | PowerPoint Copilot Skill Library |
| Kaavyaa Raju Murugan | — | Prompt Library |
| Evita Mary D Silva | — | Prompt Library |
| Kirthan Radhakrishnan | — | AI Events Playbook |

---

## Repository Structure

```
medibank-ai-enablement-toolkit/
├── excel-skills/          9 Excel Copilot custom skills (SKILL.md)
├── ppt-skills/            20 PowerPoint Copilot custom skills (SKILL.md)
├── prompt-library/        Enterprise prompt library (xlsx)
├── ai-playbook/           AI Events Playbook (docx)
└── synthetic-data/        Synthetic dataset used for testing
```

---

## Deliverable 1 · Excel Copilot Skill Library

**Owner:** Rohit Krishnan  
9 custom Microsoft 365 Copilot skills for Medibank's core Excel analytical workflows. Each skill is a SKILL.md file deployable to OneDrive and invokable via @mention in Copilot.

| Skill | @mention | Core Function |
|---|---|---|
| Anomaly Detector | @anomaly-detector | Z-score, IQR, Benford's Law, peer-group, temporal detection |
| Data Validator | @data-validator | APRA/AIHW validation; 7 rule categories; Quality Score ≥ 95% |
| Chronic Disease Cost Modeller | @chronic-disease-cost-modeller | 5-year BaU vs Managed Care DCF; NPV, IRR |
| QoQ Trend Analyser | @qoq-trend-analyser | Quarter-on-quarter KPI trend; 3-tier significance |
| Member LTV Calculator | @member-lifetime-value-calculator | DCF-based MLV; behavioural churn only; community rating safe |
| Provider Payment Reconciler | @provider-payment-reconciler | Billing vs payment reconciliation; 5 variance types |
| Hospital Gap Fee Analyser | @hospital-gap-fee-analyser | Gap Fee analysis; member OOP flagging |
| Workforce Productivity Tracker | @workforce-productivity-tracker | 3-tier Copilot adoption; ROI; Shadow IT log |
| Regulatory Submission Checker | @regulatory-submission-checker | APRA PHI quarterly return validation; 4-party sign-off |

**Deployment path:** `Documents/Copilot/Microsoft Excel/skills/<skill-folder>/SKILL.md`

---

## Deliverable 2 · PowerPoint Copilot Skill Library

**Owner:** Ngoc Anh Thu Nguyen  
20 refined PowerPoint Copilot skills for common presentation tasks, tested against synthetic materials. Includes tracking spreadsheet.

---

## Deliverable 3 · Enterprise Prompt Library

**Owners:** Kaavyaa Raju Murugan · Evita Mary D Silva  
Enterprise-ready prompts structured using the CRAFT framework (Context, Role, Action, Format, Tone) covering common knowledge-work scenarios.

---

## Deliverable 4 · AI Events Playbook

**Owner:** Kirthan Radhakrishnan  
Operational playbook for running AI Promptathons, Hackathons, and Ideation Sessions, including Risk Gate, phase-by-phase guidance, facilitator templates, scoring sheets, and lessons learned log.

---

## Synthetic Data

All development and testing used `Medibank_Synthetic_Dataset_v2.xlsx` — no real Medibank member, claims, or financial data was used at any point (clean-room approach).

---

## Notes

- All skills were tested in Microsoft 365 Copilot using personal licences and synthetic data only
- Excel SKILL.md files trimmed to 5.1–7.1 KB for Copilot compatibility
- Community rating compliance embedded in all financial models
- This toolkit is a prototype for Medibank to review and validate internally

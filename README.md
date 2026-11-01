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
| Ngoc Anh Thu Nguyen | S3912314  | PowerPoint Copilot Skill Library |
| Kaavyaa Raju Murugan | S4134222 | Prompt Library |
| Evita Mary D Silva | S4152128 | Prompt Library |
| Kirthan Radhakrishnan | S4141224 | AI Events Playbook |

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

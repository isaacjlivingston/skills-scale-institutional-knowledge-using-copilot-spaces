# OctoAcme RACI Matrix

This matrix clarifies each role's level of involvement for key project activities across the OctoAcme project management lifecycle. Use it alongside [Roles & Personas](octoacme-roles-and-personas.md) to assign tasks and set expectations with your team.

## RACI Legend

| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; final approver |
| **C** | **Consulted** — provides input before or during the activity |
| **I** | **Informed** — kept up to date on progress or decisions |

---

## Role Abbreviations

| Abbreviation | Role |
|---|---|
| PS | Project Sponsor |
| CM | Change Manager |
| PM | Project Manager |
| PdM | Product Manager |
| TL | Technical Lead |
| Dev | Developer(s) |
| QA | QA Analyst |
| SME | Subject Matter Expert |

---

## RACI by Activity

| Activity | PS | CM | PM | PdM | TL | Dev | QA | SME |
|---|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | | |
| Define project vision and goals | A | I | R | C | C | I | I | C |
| Secure project funding and resources | A | I | C | I | I | I | I | I |
| Identify and align key stakeholders | A | C | R | C | I | I | I | C |
| Complete project charter / one-pager | I | I | R | C | C | I | I | C |
| Go / No-Go decision gate | A | I | R | C | C | I | I | I |
| **Planning** | | | | | | | | |
| Define scope and acceptance criteria | I | I | R | A | C | C | C | C |
| Develop project schedule and milestones | I | C | R | C | C | I | I | I |
| Build and refine backlog / user stories | I | I | C | A | C | R | C | C |
| Establish Definition of Done | I | I | C | A | R | C | R | C |
| Create risk register | I | C | R | C | C | I | I | C |
| Plan change management activities | C | A | C | I | I | I | I | C |
| **Execution** | | | | | | | | |
| Implement features | I | I | I | C | C | R | I | I |
| Conduct code and design reviews | I | I | I | I | A | R | C | C |
| Execute test cases and report defects | I | I | I | I | C | C | R | C |
| Resolve defects and verify fixes | I | I | I | I | C | R | A | I |
| Maintain risk register | I | C | R | C | C | I | I | I |
| Weekly status update | I | I | R | C | I | I | I | I |
| Stakeholder communication | C | C | R | C | I | I | I | I |
| **Change Management** | | | | | | | | |
| Develop change management plan | C | A | C | I | I | I | I | C |
| Conduct training and readiness sessions | I | A | C | C | C | I | I | R |
| Track change adoption metrics | I | A | I | I | I | I | I | I |
| **Release & Deployment** | | | | | | | | |
| Pre-release quality sign-off | I | I | R | C | C | C | A | I |
| Deployment approval | A | I | R | C | C | I | C | I |
| Post-deployment verification | I | I | R | C | C | R | R | I |
| Release notes | I | I | R | R | C | C | I | I |
| **Retrospective & Close** | | | | | | | | |
| Facilitate retrospective | I | C | R | C | I | I | I | I |
| Capture and track action items | I | C | R | C | I | I | I | I |
| Final stakeholder debrief | A | C | R | C | I | I | I | I |

---

## Notes

- An activity must have exactly one **A** (Accountable) — if multiple roles share accountability, clarify ownership before the project starts.
- **C** (Consulted) roles should be engaged proactively; do not wait for them to ask.
- **I** (Informed) roles may only need a brief summary or status update, not a full review cycle.
- Adapt this matrix to your specific project context — not all activities apply to every project.

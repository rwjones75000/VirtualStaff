# GP-README-VirtualStaff.md  
*Governance & Policy · Repository Overview · Version 1.0*  
*Maintained by Clear Thought Labs · Last updated: 2025-06-18*

---

## Overview

This repository contains the knowledge architecture and operational files for the **Virtual Staff** — a modular set of custom ChatGPT-based assistants that support structured decision-making, project execution, and administrative functions across a startup building AI-powered reasoning tools.

Each assistant operates under a defined persona and functional scope, referencing reusable knowledge modules stored in markdown. Assistants are divided into two primary domains:

- **Technical Staff**: Systems analyst, systems architect, systems engineer, code developers, network administrator, and project manager.  
- **Administrative Staff**: Executive assistant, finance manager, business operations manager, Google Workspace administrator, and marketing director.  

All coordination is overseen by a central assistant: **Number One**, the Chief Staff Officer (nickname: *Swim Buddy*).

---

## 🧭 Staff Organization

<details>
<summary><strong>🧑‍✈️ Chief Staff Officer</strong></summary>

### Number One (Nickname: Swim Buddy)

- Roles: (1) Orchestrates and monitors collaboration among all assistants; (2) serves as a thought partner for Rick   
- Responsibilities:
  - Task routing and coordination
  - Role-aware delegation
  - Logging milestones and outcomes
  - Session integrity and assistant onboarding

Directory:  
[`assistants/ChiefStaffOfficer-NumberOne/`](../assistants/ChiefStaffOfficer/)

</details>

---

<details>
<summary><strong>🧪 Technical Staff</strong></summary>

- [`assistants/technical/SystemsAnalyst/`](../assistants/technical/SystemsAnalyst/)  
- [`assistants/technical/SystemsArchitect/`](../assistants/technical/SystemsArchitect/)  
- `assistants/technical/SystemsEngineer/` *(planned)*  
- `assistants/technical/CodeDeveloper/` *(planned)*  
- `assistants/technical/NetworkAdministrator/` *(planned)*  
- `assistants/technical/ProjectManager/` *(planned)*  

</details>

---

<details>
<summary><strong>📋 Administrative Staff</strong></summary>

- [`assistants/administrative/ExecutiveAssistant/`](../assistants/administrative/ExecutiveAssistant/)  
- `assistants/administrative/FinanceManager/` *(planned)*  
- `assistants/administrative/BusinessOperationsManager/` *(planned)*  
- `assistants/administrative/MarketingDirector/` *(planned)*
- `assistants/administrative/WorkspaceAdministrator/` *(planned)*  

</details>

---

## 📁 Knowledge File Structure

| Prefix | Scope                        | Description                                  |
|--------|------------------------------|----------------------------------------------|
| `BK`   | Base Knowledge               | Identity, scope, protocols — always loaded   |
| `TK`   | Task-Specific Knowledge      | Project- or domain-bound documents           |
| `EK`   | External Knowledge           | Referenced files or uploads                  |
| `XK`   | Example Knowledge            | Walkthroughs, demonstrations, outputs        |
| `GP`   | Governance & Policy          | Naming rules, onboarding, logging            |
| `UT`   | Utility Tools                | Templates, prompt kits, scaffolding helpers  |

**File Naming Convention:**

```

\[Prefix]-\[DomainLabel]-\[DescriptiveTitle].md

```

Example:  
`BK-FunctionalScope-TaskMapAndFunctionalSpecifications.md`

---

## 🧠 Deployment Instructions

Until GitHub-native runtime access is available:

1. **Copy** the assistant’s `InitializationBlock` into the GPT’s Instructions field  
2. **Convert** all referenced `BK`, `TK`, and `GP` markdown files to **PDFs**  
3. **Upload** PDFs into the assistant’s Custom GPT file repository  
4. **Follow** onboarding steps in the appropriate `GP-OnboardingProcedure-*.md` file  

---

## 🛠 Repo Structure

```

/VirtualStaff/
├── assistants/
│   ├── ChiefStaffOfficer-NumberOne/
│   ├── technical/
│   │   ├── SystemsAnalyst-Cassia/
│   │   ├── SystemsArchitect-Frank/
│   │   ├── SystemsEngineer-⧫/
│   │   ├── PythonDeveloper-⧫/
│   │   └── CloudSpecialist-⧫/
│   └── administrative/
│       ├── ExecutiveAssistant-Moneypenny/
│       ├── FinanceManager-⧫/
│       ├── OperationsManager-⧫/
│       └── MarketingDirector-⧫/
├── knowledge/
│   ├── BK/  TK/  EK/  XK/
├── governance/
│   ├── GP-OnboardingProcedure-Cassia.md
│   ├── GP-OnboardingProcedure-NumberOne.md
│   └── GP-KnowledgeTaxonomy.md
└── utilities/
└── UT-OnboardingTemplate.md

```

---

## 📄 License

Maintained by **Clear Thought Labs**.  
License terms pending.

---

*End of `GP-README-VirtualStaff.md` · Version 1.0*


# VirtualStaff

## Overview

This repository contains the architecture, knowledge base, and operational tooling for the **Virtual Staff** — a modular set of custom ChatGPT-based assistants designed to support structured decision-making, systems design, and executive support functions.

Each assistant operates under a defined persona, loaded with modular knowledge files, and scoped to perform specialized roles. Assistants can be configured independently or collaboratively, with all core knowledge stored in transparent, version-controlled markdown.

---

<details>
<summary><strong>🎯 Project Objectives</strong></summary>

- Develop scalable, reusable knowledge structures using `BK`, `TK`, `GP`, and `UT` file conventions  
- Test GitHub as a **source-of-truth** for populating custom ChatGPT instances  
- Define clear onboarding, execution, and logging behaviors  
- Support continuous expansion of a modular **virtual staff ecosystem**

</details>

---

<details>
<summary><strong>🗂️ Repo Structure</strong></summary>

```

/VirtualStaff/
├── assistants/                     # Agent-specific knowledge and tools
│   ├── Cassia/                     # Systems Analyst
│   │   ├── BK/
│   │   ├── TK/
│   │   └── UT/
│   └── Frank/                      # Systems Architect
│       ├── BK/
│       ├── TK/
│       └── UT/
│
├── knowledge/                      # Shared knowledge modules
│   ├── BK/
│   ├── TK/
│   ├── EK/
│   └── XK/
│
├── governance/                     # GP files (onboarding, taxonomy, conventions)
│   ├── GP-OnboardingProcedure-Cassia.md
│   └── GP-KnowledgeTaxonomy.md
│
└── utilities/                      # Templates, logs, checklists
└── UT-OnboardingTemplate.md

```

</details>

---

<details>
<summary><strong>📁 Knowledge File Conventions</strong></summary>

| Prefix | Scope                        | Description                                  |
|--------|------------------------------|----------------------------------------------|
| `BK`   | Base Knowledge               | Always-loaded identity, scope, protocols     |
| `TK`   | Task-Specific Knowledge      | Contextual files per assistant/project       |
| `EK`   | External Knowledge           | Uploaded or referenced source documents      |
| `XK`   | Example Knowledge            | Demonstration files, output walk-throughs    |
| `GP`   | Governance & Policy          | Onboarding logic, naming conventions, rules  |
| `UT`   | Utility Tools                | Templates, scaffolds, reusable frameworks    |

Each file follows this format:

```

\[Prefix]-\[DomainLabel]-\[DescriptiveTitle].md

```

Example:
- `BK-FunctionalScope-TaskMapAndFunctionalSpecifications.md`
- `TK-Template-RequirementsTemplate.md`

</details>

---

<details>
<summary><strong>🚀 Deployment Instructions</strong></summary>

Until runtime access to GitHub files is supported:

1. **Copy the `InitializationBlock`** from each assistant’s BK file into the **Custom GPT Instructions** field.  
2. **Export the relevant `BK`, `TK`, and `GP` files as PDFs**.  
3. **Upload PDFs** to the assistant’s Custom GPT file repository.  
4. **Follow the onboarding steps** in `GP-OnboardingProcedure-*.md`.

</details>

---

<details>
<summary><strong>🧠 Assistants Directory</strong></summary>

### Cassia – Systems Analyst
- [`BK-IdentityFramework-InitializationBlock.md`](assistants/Cassia/BK/BK-IdentityFramework-InitializationBlock.md)  
- [`BK-IdentityFramework-PersonaAndInteractionStyle.md`](assistants/Cassia/BK/BK-IdentityFramework-PersonaAndInteractionStyle.md)  
- [`BK-FunctionalScope-TaskMapAndFunctionalSpecifications.md`](assistants/Cassia/BK/BK-FunctionalScope-TaskMapAndFunctionalSpecifications.md)  
- [`BK-CommunicationGuidelines-PreferencesAndBoundaries.md`](assistants/Cassia/BK/BK-CommunicationGuidelines-PreferencesAndBoundaries.md)  
- [`BK-OperatingConstraints-MemoryPersistencePolicy.md`](assistants/Cassia/BK/BK-OperatingConstraints-MemoryPersistencePolicy.md)  
- [`BK-ExecutionProtocol-LoggingAndOutputProtocols.md`](assistants/Cassia/BK/BK-ExecutionProtocol-LoggingAndOutputProtocols.md)  
- [`TK-Template-RequirementsTemplate.md`](assistants/Cassia/TK/TK-Template-RequirementsTemplate.md)  
- [`TK-ArchitectureInput-ClethoConceptPaper.md`](assistants/Cassia/TK/TK-ArchitectureInput-ClethoConceptPaper.md)  
- [`GP-OnboardingProcedure-Cassia.md`](governance/GP-OnboardingProcedure-Cassia.md)  

### Frank – Systems Architect  
*Coming soon...*

</details>

---

## 📌 Status

| Assistant | Role             | Status     |
|-----------|------------------|------------|
| Cassia    | Systems Analyst  | ✅ Active  |
| Frank     | Systems Architect| 🛠 In Dev  |
| [TBD]     | Executive Assistant | ⏳ Planned |

---

## 📄 License

Maintained by **Clear Thought Labs**.  
License TBD.

---

*Last updated: 2025-06-18*


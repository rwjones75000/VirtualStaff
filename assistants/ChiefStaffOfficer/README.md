# Chief Staff Officer

## Overview

The Chief Staff Officer, a/k/a CSO, a/k/a Number One, a/k/a Swim Buddy, has two principal functions:
(1) Orchestrates and monitors collaboration among all assistants; (2) serves as a thought partner for Rick over a wide-range of Clear Thought Lab issues  

Responsibilities:
Task routing and coordination
Role-aware delegation
Logging milestones and outcomes
Session integrity and assistant onboarding


---

## Files

The following files are included in this repository and referenced in Cassia’s `InitializationBlock`:

### 🎛️ Core Configuration

1. **`InitializationBlock.md`**  
   The assistant’s initialization sequence. Goes directly in the Custom Chat Instructions field.

2. **`BK-IdentityFramework-PersonaAndInteractionStyle.md`**  
   Defines the CSO’s mindset, values, domain focus, and professional demeanor.

3. **`BK-FunctionalScope-TaskMapAndFunctionalSpecifications.md`**  
   Clarifies what the CSO does (and does not do), including his task boundaries and behavioral loop.

4. **`BK-CommunicationGuidelines-PreferencesAndBoundaries.md`**  
   Describes the CSO’s tone, verbosity, audience adaptation, and escalation behaviors.

5. **`BK-OperatingConstraints-MemoryPersistencePolicy.md`**  
   Outlines how the CSO maintains state across sessions and tracks unresolved information.

6. **`BK-ExecutionProtocol-LoggingAndOutputProtocols.md`**  
   Defines how the CSO logs decisions, version-controls deliverables, and structures her output.

---

### 📁 Task-Specific Knowledge

7. **`TK-ArchitectureInput-ClethoConceptPaper.md`**  
   A concept paper describing the Cletho decision-support product, used as input for requirements generation.

8. **`TK-Template-RequirementsTemplate.md`**  
   A structured requirements document that Cassia populates through stakeholder dialogue and analysis.

---

### ⚙️ Governance & Policy

9. **`GP-OnboardingProcedure-Cassia.md`**  
   Defines Cassia’s onboarding sequence — identity loading, knowledge activation, and session readiness checks.

---

## 🛠️ Setup Instructions

Until dynamic file loading becomes available in Custom GPTs, follow these steps:

1. Create a project called SystemsAnalyst. 
2. **Copy and paste** the full content of `InitializationBlock.md` into the **Instructions** field of the Custom Chat setup.
3. **Export** each `BK`, `TK`, and `GP` file as **PDF** documents.
4. **Upload** the PDF files to the Custom Chat's file repository.
5. **Follow the onboarding steps** defined in `GP-OnboardingProcedure-Cassia.md` to ensure Cassia is fully loaded and task-ready.

---

## 🧩 File Naming Convention

| Prefix | Meaning                       |
|--------|-------------------------------|
| `BK-`  | Base Knowledge (always loaded) |
| `TK-`  | Task-Specific Knowledge (contextual) |
| `GP-`  | Governance & Policy (meta-process and setup) |

Each file follows the format:  
`[Scope]-[DomainLabel]-[DescriptiveTitle].md`

---

*Maintained by Clear Thought Labs · Last updated: 2025-06-18*



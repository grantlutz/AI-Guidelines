# AI Assistant Start Here

**Owner:** <Your name>  
**Workspace:** `<workspace-root>/`  
**Status:** Active  
**Version:** 1.0  
**Location:** Workspace root — canonical entry point

## IMPORTANT

Do not recommend folder reorganizations unless explicitly requested.

Favor content creation over repository restructuring.

When you make a structural or architectural decision, record it with `Decisions_ADR/ADR-0000-template.md`. Do not assume a baseline architecture already exists.

## Purpose

This file is the required entry point for substantive work in this workspace. Before creating, revising, summarizing, or recommending work, load the governing documents and relevant product references listed below.

## Path Convention

All paths in this file are relative to the **workspace root** (`<workspace-root>/`). This file lives at the workspace root as `00_COPILOT_START_HERE.md` and is the canonical repository entry point.

## Governing Order

1. `CONSTITUTION.md` (workspace root)
2. This file, `00_COPILOT_START_HERE.md`
3. Accepted records in `Decisions_ADR/` (use `Decisions_ADR/ADR-0000-template.md` when recording a new decision)
4. Task-specific playbooks and product references
5. `Engineering_Standards/Style_Guides/Reference/INDEX_MASTER_GUIDE.md`
6. Relevant format-specific style guide
7. User instructions for the current task

If two instructions conflict, stop, identify the conflict, explain both positions, and recommend a direction based on `CONSTITUTION.md`.

## Required Startup Sequence

1. Read `CONSTITUTION.md`. This file is required.
2. Read `Governance/WORKSPACE_OPERATING_MODEL.md`.
3. Read `Governance/WORKSPACE_INDEX.md` to discover registered durable material.
4. Review `Decisions_ADR/` for accepted decisions. Use `Decisions_ADR/ADR-0000-template.md` only as a template when recording a new decision.
5. Identify the product or service involved.
6. Search for an existing playbook, reference, template, prior deliverable, or documented decision.
7. Read the relevant style guide for the requested output type, if one applies.
8. Verify facts against authoritative sources.
9. Create the deliverable in the appropriate workspace folder.
10. Run the relevant quality and compliance checklist before finalizing.

## Bootstrap Validation

Treat file references as **required** or **optional**.

**Required** (ships with this template; stop if missing):

- `CONSTITUTION.md`
- This file, `00_COPILOT_START_HERE.md`

If a required file cannot be located:

1. Stop bootstrap processing.
2. Record the missing reference.
3. Report the missing reference to the user before proceeding.
4. Do not substitute a similar-looking file, and do not recreate a missing required document from memory or inference.

**Optional placeholders** (also ship with this template as stubs you should customize). If one is missing, **warn** the user, record the gap, and continue if the current task can proceed without it. Do not invent a replacement.

- `Governance/WORKSPACE_OPERATING_MODEL.md`
- `Governance/WORKSPACE_INDEX.md`
- `Decisions_ADR/ADR-0000-template.md`
- `Engineering_Standards/Email-Template.md`
- `Engineering_Standards/Style_Guides/Reference/INDEX_MASTER_GUIDE.md`
- Format-specific style guides listed under Output Routing

**Task-specific / only if present.** Product playbooks such as `Products/<Product>/Playbooks/<Product>-Alert-Triage-Playbook.md` do not ship with this template. If a referenced product file is missing, warn the user and continue; do not create it unless asked.

**Never silently skip a required governance document.** A skipped constitution produces work that looks compliant and is not, which is worse than work that visibly failed to start.

## Core Operating Principles

- Never guess or fabricate information.
- Check existing workspace documentation before asking questions.
- Verify facts when uncertainty or hallucination risk exists.
- Identify factual gaps explicitly.
- Flag conflicts between instructions or documents.
- Reuse approved templates before creating a new format.
- Keep outputs concise, complete, action-oriented, and practical.
- Distinguish facts, analysis, recommendations, and assumptions.
- Cite or identify source material when the work depends on it.

## Default Workspace

Unless otherwise specified, create and organize work under:

`<workspace-root>/`

Do not overwrite source files. Use a new version unless the user explicitly requests an update to the existing file.

## Product and Service Scope

<Your name> is the <role> for:

- <product/service>
- <product/service>
- <product/service>

Before creating product-specific work, check the corresponding product folder and related playbooks.

## Output Routing

- Email drafts: use `Engineering_Standards/Email-Template.md`.
- Written documentation: use `Engineering_Standards/Style_Guides/Documentation/03_DOCUMENTATION_STYLE_GUIDE.md`.
- Presentations: use `Engineering_Standards/Style_Guides/PowerPoint/01_POWERPOINT_STYLE_GUIDE.md`.
- Architecture diagrams: use `Engineering_Standards/Style_Guides/Architecture/02_ARCHITECTURE_STYLE_GUIDE.md`.
- Brand, colors, fonts, and classification: use `Engineering_Standards/Style_Guides/Root_Standards/00_ROOT_STYLE_GUIDE.md`.
- Template reuse: use `Engineering_Standards/Style_Guides/PowerPoint/04_EXAMPLE_WORK_LEVERAGE_GUIDE.md`.
- Alert triage (optional; only if you have added the product playbook): use `Products/<Product>/Playbooks/<Product>-Alert-Triage-Playbook.md`.

## Default Trigger Phrase

When the user says **"Bootstrap from this workspace"** or **"Use workspace standards"**, execute the Required Startup Sequence before beginning substantive work.

## Finalization Check

Before delivering work, confirm:

- The constitution was followed.
- Relevant existing material was checked.
- Facts were verified.
- Assumptions and gaps were disclosed.
- The correct template and style guide were used, or their absence was disclosed.
- The filename, version, date, and classification are appropriate.
- The final file is organized in the correct workspace folder.

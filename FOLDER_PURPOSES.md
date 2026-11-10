# Folder Purposes

**Version:** 1.0  
**Status:** Active  
**Governed By:** `CONSTITUTION.md`

This document is the single-sentence test for where anything belongs. If a file satisfies two entries, it is ambiguous: leave it where it is and record a recommendation rather than guessing.

This template ships **18** top-level folders.

## Top-Level Folders

| Folder | Purpose | Decision Test |
|--------|---------|---------------|
| `Governance` | Binding rules for how the workspace operates | "Does this constrain how other work is done?" |
| `Products` | Durable, product-scoped knowledge by service | "Is this specific to one named product?" |
| `Templates` | Reusable, unfilled source material | "Would I open this to start something new?" |
| `Playbooks` | Cross-product repeatable procedures | "Is this steps-to-follow, not tied to one product?" |
| `Engineering_Standards` | Format, documentation, and communication standards | "Does this define how output should look or read?" |
| `Architecture_Repository` | Reusable diagrams and architecture exemplars | "Is this a diagram or architecture artifact worth reusing?" |
| `Executive_Communications` | Finished leadership-facing output | "Was this written to be read by an executive?" |
| `Project_Records` | Point-in-time project history | "Is this a record of what happened?" |
| `TPM_Toolkit` | Program management instruments | "Is this how I run the portfolio?" |
| `Decisions_ADR` | Architecture decision records | "Is this a decision I do not want to re-argue?" |
| `Incidents` | Incident records and post-incident reviews | "Did something break?" |
| `Knowledge_Base` | Durable generalized knowledge | "Is this useful outside the event that produced it?" |
| `Working` | Scratch space, nothing authoritative | "Is this still in flight?" |
| `Archive` | Superseded material, retained not deleted | "Is this replaced but worth keeping?" |
| `Coding` | Scripts, utilities, and automation | "Is this code or a script, not a durable product record?" |
| `Company_Templates` | Organization-specific templates | "Is this a template unique to this organization?" |
| `Example_Work` | Sample deliverables and reference outputs | "Is this an example others can learn from?" |
| `Meeting_Notes` | Meeting documentation and actions | "Is this a record of a meeting?" |

## Product Subfolder Pattern

Every product under `Products/` uses the same five subfolders so location is predictable without exploring. Add these when you introduce a product; they are not pre-created.

| Subfolder | Purpose |
|-----------|---------|
| `Reference` | Current-state facts: how the service is configured and behaves |
| `Roadmaps` | Forward-looking plans, migrations, and planned change |
| `Service_Reviews` | Periodic operational and vendor review material |
| `Architecture` | The architecture of record for that product |
| `Playbooks` | Product-specific operational procedures |

Example products: `<Product A>`, `<Product B>`, `<Product C>`, `<Product D>`.

## TPM_Toolkit Subfolders

These are suggested subfolders you may add under `TPM_Toolkit/`.

| Subfolder | Purpose |
|-----------|---------|
| `Stakeholder_Maps` | Who matters, their influence, and the engagement model |
| `KPI_Catalog` | Defined measures, their sources, and their owners |
| `Risk_Register` | Open risks, owners, mitigations, and status |
| `Quarterly_Planning` | Planning inputs and commitments by quarter |

## Boundaries That Are Easy to Get Wrong

- **Governance vs Engineering_Standards** - Governance says how the workspace operates; Engineering_Standards says how output should look. A style guide is a standard, not governance.
- **Templates vs Executive_Communications** - A blank one-pager template is a Template. A completed one-pager about a real initiative is an Executive Communication.
- **Products/Architecture vs Architecture_Repository** - The architecture of record for a product lives with the product. Reusable diagrams and exemplars live in the repository.
- **Playbooks vs Products/Playbooks** - If it only applies to one product, it belongs to that product.
- **Incidents vs Knowledge_Base** - The incident record stays in Incidents. The generalized lesson is promoted to Knowledge_Base.
- **Project_Records vs Products** - Project_Records is history. Products is current truth.

# How to Adopt and Transform the AI Guidelines Starter Workspace

Welcome! This guide will help you understand the structure, adopt it for your organization, and transform it to fit your unique needs.

---

## Table of Contents

1. [Quick Start](#quick-start)
2. [Understanding the Structure](#understanding-the-structure)
3. [Folder Purposes & Customization](#folder-purposes--customization)
4. [The Constitution](#the-constitution)
5. [Step-by-Step Adoption Guide](#step-by-step-adoption-guide)
6. [Transformation Tips](#transformation-tips)
7. [Best Practices](#best-practices)

---

## Quick Start

**What You Have**:
- A pre-built folder structure designed for organization, governance, and knowledge management
- A CONSTITUTION.md that establishes guidelines for AI interactions
- Clear documentation on folder purposes and usage

**What You Need to Do**:
1. Rename folders to match your organization's terminology
2. Populate folders with your organization's content
3. Customize the CONSTITUTION.md to reflect your values
4. Train your team on the structure

---

## Understanding the Structure

This template includes **18 core folders**:

### 1. **Architecture_Repository**
- **Purpose**: Store technical architecture diagrams, decision records, and system design documentation
- **Common Files**: Architecture Decision Records (ADRs), system diagrams, component relationships
- **Customize For**: Your tech stack, microservices, infrastructure, or design patterns

### 2. **Coding**
- **Purpose**: Development scripts, automation code, and technical tools
- **Common Files**: Scripts, utilities, automation tools, sample code
- **Customize For**: Your language stack, CI/CD tools, deployment scripts

### 3. **Decisions_ADR**
- **Purpose**: Architecture Decision Records - formalized decisions and rationale
- **Common Files**: ADR templates, decision logs with context and trade-offs
- **Customize For**: Your decision-making framework and governance process

### 4. **Engineering_Standards**
- **Purpose**: Style guides, coding standards, and quality benchmarks
- **Common Files**: Style guides, templates, linting rules, quality gates
- **Customize For**: Your tech stack and team preferences

### 5. **Example_Work**
- **Purpose**: Reference materials and sample outputs
- **Common Files**: Templates, sample reports, documentation examples
- **Customize For**: Typical deliverables in your organization

### 6. **Executive_Communications**
- **Purpose**: High-level summaries, executive briefs, strategic updates
- **Common Files**: One-pagers, executive summaries, board materials
- **Customize For**: Your executive structure and reporting cadence

### 7. **Governance**
- **Purpose**: Policies, compliance frameworks, audit trails, and risk management
- **Common Files**: Policy documents, audit logs, compliance checklists, risk registers
- **Customize For**: Your compliance requirements and governance model

### 8. **Incidents**
- **Purpose**: Incident tracking, postmortems, and root cause analyses
- **Common Files**: Incident logs, RCA templates, timeline documentation
- **Customize For**: Your incident management and learning culture

### 9. **Knowledge_Base**
- **Purpose**: Organizational learning, patterns, lessons learned, and historical context
- **Suggested subfolders** (add these if you need them):
  - `Historical_Context`: Past decisions, migrations, major changes
  - `Lessons_Learned`: Retrospectives, what worked, what didn't
  - `Migration_Knowledge`: Change management documentation
  - `Operational_Intelligence`: Best practices, runbooks
  - `Patterns`: Reusable solutions and anti-patterns
  - `Vendor_Intelligence`: Third-party integrations, product evaluations
- **Customize For**: Your domain expertise and institutional memory

### 10. **Meeting_Notes**
- **Purpose**: Centralized meeting documentation and action items
- **Common Files**: Meeting notes, action item tracking
- **Customize For**: Your meeting cadence and team structure

### 11. **Playbooks**
- **Purpose**: Step-by-step procedures and operational runbooks
- **Common Files**: Checklists, procedures, troubleshooting guides
- **Customize For**: Your common operational scenarios

### 12. **Products**
- **Purpose**: Product-specific documentation and knowledge
- **Common Files**: Product docs, feature tracking, roadmaps
- **Customize For**: Your product portfolio or key systems

### 13. **Project_Records**
- **Purpose**: Project-specific documentation and history
- **Common Files**: Project charters, status reports, deliverables
- **Customize For**: Your project management methodology

### 14. **Company_Templates**
- **Purpose**: Organization-specific templates and standards
- **Customize For**: Your company name and standard templates

### 15. **Templates**
- **Purpose**: Reusable document and communication templates
- **Subfolders**: Images, PowerPoint, Reports
- **Customize For**: Your brand guidelines and common document types

### 16. **TPM_Toolkit** *(or customize the name)*
- **Purpose**: Technical Program Management resources
- **Suggested subfolders** (add these if you need them):
  - `Executive_Review_Templates`: Stakeholder update formats
  - `KPI_Catalog`: Metrics and measurement frameworks
  - `Product_Charter_Templates`: Initiative documentation
  - `Quarterly_Planning`: Strategic planning resources
  - `Risk_Register`: Risk tracking and mitigation
  - `Service_Catalog`: Service definitions
  - `Service_Definition_Templates`: Service level documentation
  - `Stakeholder_Maps`: Organizational relationships
- **Customize For**: Your management framework (could be PMP, Agile, Scrum, etc.)

### 17. **Working**
- **Purpose**: Active workspace for current projects and work-in-progress
- **Customize For**: Your active initiatives

### 18. **Archive**
- **Purpose**: Superseded material that should be retained, not deleted
- **Common Files**: Retired documents, superseded plans, closed-project records
- **Customize For**: Your retention and records policy

---

## Folder Purposes & Customization

### How to Customize Folder Names

The template uses descriptive, professional naming. You may want to adjust:

| Template Name | Possible Customizations |
|---|---|
| Company_Templates | YourCompany_Templates, Org_Templates |
| TPM_Toolkit | Scrum_Toolkit, PM_Toolkit, Project_Management, Strategy_Toolkit |
| Engineering_Standards | Development_Standards, Code_Standards, Technical_Standards |
| Executive_Communications | Leadership_Comms, Board_Materials, C-Suite_Updates |
| Decisions_ADR | Architecture_Decisions, Technical_Decisions, Decisions |

### When to Add Folders

Consider adding folders for:
- Frequently accessed content not in the template (e.g., `Client Work`, `Research`, `Vendor Relationships`)
- Organizational structure (e.g., `Department_Finance`, `Department_HR`)
- Geographic regions (e.g., `North America`, `EMEA`)
- Compliance domains (e.g., `ISO27001`, `HIPAA`, `GDPR`)

### When to Remove Folders

Remove folders that don't apply to your organization:
- `Incidents` (if you don't track incidents separately)
- `TPM_Toolkit` (if you don't do technical program management)
- `Playbooks` (if you use a separate system for runbooks)

---

## The Constitution

The `CONSTITUTION.md` file establishes how you and your AI assistant will interact.

### Key Principles in This Constitution

1. **Never Guess** - Your AI assistant will ask for clarity rather than assume
2. **Hallucination Detection** - Your AI assistant will verify information and disclose uncertainty
3. **Clarity Before Action** - Your AI assistant will ask questions before proceeding
4. **Conflict Detection** - Your AI assistant will flag conflicts and ask for direction
5. **Documentation Hierarchy** - Constitution is the root authority

### Customizing the Constitution

You may want to adjust for your organization:

- **Add specific communication preferences** (e.g., "Always summarize in bullet points")
- **Add risk tolerances** (e.g., "When uncertain, stop and ask" vs. "When uncertain, take reasonable best approach")
- **Add domain-specific rules** (e.g., "All decisions must be auditable" or "Never commit secrets to repositories")
- **Adjust scope** (e.g., apply only to this folder, or across all your projects)

**Edit the Constitution when:**
- Your team's needs or values change
- You encounter repeated conflicts or misunderstandings
- Your organization's compliance or risk profile changes
- You want to add new capabilities or constraints

---

## Step-by-Step Adoption Guide

### Phase 1: Foundation (Week 1)

**Goal**: Set up and understand the structure.

1. **Review this guide** - Spend 30 minutes understanding all sections
2. **Read CONSTITUTION.md** - Understand how your AI assistant will interact with you
3. **Customize folder names** - Rename folders to match your terminology
4. **Create a README** - Add a file in the root explaining your workspace
5. **Set permissions** - If shared, configure who can access which folders

**Deliverable**: A clean, renamed folder structure with basic documentation.

---

### Phase 2: Population (Weeks 2-4)

**Goal**: Start moving content into the structure.

1. **Audit existing content** - Gather all documentation from your organization
2. **Categorize content** - Assign each document to the appropriate folder
3. **Create folder README files** - Add brief descriptions to each folder (optional but recommended)
4. **Establish naming conventions** - Create a consistent file naming scheme
5. **Import high-priority content** - Start with governance, standards, and playbooks

**Deliverable**: 50-70% of your existing documentation migrated into the structure.

---

### Phase 3: Operationalization (Weeks 5-8)

**Goal**: Integrate the workspace into your daily workflow.

1. **Train your team** - Explain the structure and where to find content
2. **Create a usage guide** - Document how your team should use each folder
3. **Establish content governance** - Who maintains what? How often is content reviewed?
4. **Set up templates** - Customize templates for your most common documents
5. **Create a feedback loop** - How will the team suggest structure improvements?

**Deliverable**: Your team regularly uses the workspace for their work.

---

### Phase 4: Optimization (Ongoing)

**Goal**: Continuously refine based on usage and feedback.

1. **Monthly reviews** - Check what's working and what isn't
2. **Retire stale content** - Archive outdated documentation
3. **Update the Constitution** - Adjust guidelines based on experience
4. **Refine folder structure** - Move things around if the structure doesn't match workflow
5. **Measure success** - Track adoption metrics and satisfaction

**Deliverable**: A living, continuously improving knowledge system.

---

## Transformation Tips

### Tip 1: Start Small
Don't try to migrate everything at once. Start with your highest-impact documentation (governance, standards, playbooks) and expand from there.

### Tip 2: Make It Your Own
This template is a starting point. Your organization's context should drive customization. If a folder doesn't fit your workflow, change it.

### Tip 3: Document Your Decisions
Create ADRs for significant structural or process decisions. This makes decisions transparent and searchable.

### Tip 4: Link Everything
Within your documentation, create links between related documents. This helps people navigate and understand context.

### Tip 5: Version Your Constitution
When you update the CONSTITUTION.md, keep a change log. This helps people understand how expectations have evolved.

### Tip 6: Use Consistent Metadata
Consider adding metadata to documents (date created, owner, review date, status) to make maintenance easier.

### Tip 7: Create Entry Points
Create clear README files that help people know where to start. Example:
- "New employee? Start in Knowledge_Base/"
- "Need a template? Go to Templates/"
- "Looking for standards? See Engineering_Standards/"

---

## Best Practices

### 1. Governance & Ownership

- **Assign owners** to each folder (who is responsible for maintaining it?)
- **Set review schedules** (when should content be reviewed and updated?)
- **Create an archive process** (where do old documents go?)

### 2. Documentation Quality

- **Use clear titles** that describe content, not dates (❌ "Report_Aug2026" → ✅ "Q3_2026_Performance_Report")
- **Include summaries** at the top of long documents so people know what they're reading
- **Date everything** (creation date and last review date at minimum)
- **Link related documents** so people can navigate context

### 3. Using the Constitution

- **Reference it in conflicts** - When there's confusion about process or approach, point to the relevant principle
- **Make it visible** - Consider adding a link to CONSTITUTION.md in your team workspace or documentation hub
- **Review it quarterly** - Check if the principles still align with your organization's needs

### 4. Content Maintenance

- **Create a content calendar** - What documents need review this month?
- **Establish freshness criteria** - How old can a document be before it needs review?
- **Track dependencies** - Which documents depend on others being accurate?

### 5. Knowledge Sharing

- **Highlight updates** - When you add important new content, let your team know
- **Create learning paths** - Guide new people through the most important documents first
- **Encourage contributions** - Make it easy for people to add and update content

### 6. Using Your AI Assistant Effectively

You can use Copilot, ChatGPT, Claude, or another AI assistant with this workspace.

- **Follow the Constitution** - Your AI assistant should ask clarifying questions and verify information
- **Provide context** - The more background you give, the better your AI assistant can help
- **Verify AI work** - Always double-check your AI assistant's output, especially for critical decisions
- **Use your AI assistant to organize** - Ask it to help categorize content, create summaries, or suggest structure improvements

---

## Next Steps

1. **Customize the folder names** to match your organization
2. **Review and edit CONSTITUTION.md** to reflect your values and constraints
3. **Create a root README.md** that explains your workspace
4. **Invite your team** and conduct a brief orientation (30 minutes)
5. **Start migrating content** using the Phase 1-4 adoption guide

---

## Questions?

If you encounter situations not covered by this guide:
1. Check if the CONSTITUTION.md has guidance
2. Ask yourself: "Does this decision align with our values?"
3. If still unclear, create a decision record (ADR) explaining your choice
4. Review and iterate quarterly

---

**Last Updated**: 2026-11-10  
**Status**: Template Ready for Adoption

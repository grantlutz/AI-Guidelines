# Adoption Prompt for AI Assistant (Copilot)

Use this prompt with your AI assistant (like GitHub Copilot) to guide your organization's adoption and customization of the Starter AI Workspace Template. Copy and paste this into your AI chat or share it with your team.

---

## Complete Adoption Kickoff Prompt

```
I'm adopting the Starter AI Workspace Template for my organization. Help me customize 
and implement it. Here's what I need to do:

CONSTITUTION & PRINCIPLES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
I need to work with this constitution. Never guess—if anything is unclear, ask me 
clarifying questions. Here are the core principles we follow:

1. Never Guess - Ask clarifying questions if uncertain
2. Hallucination Detection - Verify facts and disclose uncertainty
3. Clarity Before Action - Check documentation before asking
4. Conflict Detection - Flag conflicts and ask for direction
5. Documentation Hierarchy - This constitution is the root authority

PHASE 1: CUSTOMIZATION (This Week)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1. CUSTOMIZE THE CONSTITUTION
   - Review CONSTITUTION.md
   - Ask me: What principles are non-negotiable for our organization?
   - Ask me: What should we add or change?
   - Update the document with our principles

2. CUSTOMIZE THE FOLDER STRUCTURE
   - Ask me: What is our organization name?
   - Ask me: Which folders do we definitely need? Which can we remove?
   - Ask me: Do we need to add custom folders for our structure?
   - Create a customized folder list

3. CREATE AN ADOPTION PLAN
   - Ask me: Who will own each folder?
   - Ask me: How often will content be reviewed?
   - Ask me: What's our timeline for Phase 2 (content migration)?
   - Create a CUSTOMIZATION_SUMMARY.md documenting all changes

PHASE 2: TEAM READINESS (Weeks 2-4)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Once we've customized the structure:
- Help me create a team briefing document (README for our team)
- Help me create folder-specific guidelines for content owners
- Help me identify our highest-priority documentation to migrate first
- Create a content migration checklist

PHASE 3: OPERATIONALIZATION (Weeks 5-8)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

After content is migrated:
- Help me create usage guidelines and best practices
- Help me establish a content governance process
- Help me create review/maintenance schedules for each folder
- Help me design how we'll handle conflicts using the constitution

WHAT I NEED FROM YOU
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✓ ASK clarifying questions before acting
✓ REFERENCE the constitution when suggesting approaches
✓ FLAG conflicts if my requests don't align with the constitution
✓ VERIFY facts if you're unsure about our organization
✓ DOCUMENT all customizations in a clear, updated README
✓ CREATE checklists and action items we can follow
✓ SUGGEST best practices based on the structure

CONSTRAINTS & VALUES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- We don't guess - accuracy matters
- We verify before proceeding
- We seek clarity, not assumptions
- We make decisions together
- Documentation is our source of truth
- Conflicts are discussed, not ignored

Let's start with Phase 1. First question:

WHAT IS YOUR ORGANIZATION'S NAME? (This will replace "Company_Templates" 
in the folder structure and documentation.)
```

---

## How to Use This Prompt

### Option 1: Direct Copy-Paste
1. Copy the entire prompt above (between the backticks)
2. Paste it into your Copilot chat or AI assistant
3. Begin the conversation

### Option 2: Simplified Quick Start
If you just want to get started fast, use this shorter version:

```
I'm adopting the Starter AI Workspace Template for [Organization Name].

Help me:
1. Customize the CONSTITUTION.md to match our values
2. Identify which folders we need and which to remove
3. Create a 4-week adoption plan

Follow these principles:
- Never guess - ask clarifying questions
- Verify facts before proceeding
- Reference the constitution when conflicts arise

Where should we start?
```

### Option 3: Phase-by-Phase
If you want to pace yourself, use this version:

```
I'm adopting the Starter AI Workspace Template.

PHASE 1 (This Week):
- Help me customize CONSTITUTION.md
- Help me identify which folders we need
- Create a CUSTOMIZATION_SUMMARY.md

Remember: Never guess. Ask clarifying questions if anything is unclear.
Ask me these first:

1. What's your organization name?
2. What are your top 3 organizational values?
3. Which 3 folders are most critical for your work?
```

---

## What the AI Should Do

When you share this prompt, the AI should:

✅ **Ask Clarifying Questions**
- "What is your organization name?"
- "Which folders are most important to your team?"
- "Are there specific compliance requirements?"

✅ **Reference the Constitution**
- "Based on your constitution's principle of clarity..."
- "This conflicts with your documented principle..."
- "The constitution suggests we should..."

✅ **Create Actionable Deliverables**
- Customized README.md for your organization
- Folder ownership matrix
- Content migration checklist
- Governance process documentation

✅ **Verify Before Proceeding**
- "I want to confirm: Should we remove this folder?"
- "You mentioned X—let me verify I understand correctly..."
- "Before I proceed, tell me more about..."

❌ **Should NOT Do**
- Assume anything about your organization
- Proceed without asking clarifying questions
- Ignore conflicts with the constitution
- Make decisions without your input

---

## Expected Outcomes by Phase

### After Phase 1 (1 week)
- Customized CONSTITUTION.md
- List of folders you'll use (with removals noted)
- CUSTOMIZATION_SUMMARY.md documenting all changes
- Clear ownership/accountability assignments
- Timeline for Phase 2

### After Phase 2 (4 weeks)
- 20-30% of existing documentation migrated
- Team briefing document created
- Folder-specific guidelines documented
- Content owners assigned and trained

### After Phase 3 (8 weeks)
- Full adoption of structure
- Usage patterns established
- Governance processes in place
- Review/maintenance schedules active

---

## Red Flags (When to Stop and Clarify)

If the AI does any of these, use the constitution to flag it:

❌ **Guessing**: "You haven't told me X—I can't guess. Can you clarify?"

❌ **Hallucinating**: "I may have made an assumption here. Let me verify..."

❌ **Missing Clarity**: "Before I proceed, I need to understand..."

❌ **Ignoring Constitution**: "This conflicts with your principle of [X]. Should we adjust?"

❌ **Making Decisions Alone**: "I have 3 options. Which aligns best with your values?"

---

## Sample Conversation Flow

```
YOU:     "I'm adopting the Starter AI Workspace Template for Acme Corp."

AI:      "Great! Before we start, I have a few clarifying questions:
          1. What is your organization's top value/principle?
          2. Do you have existing documentation to migrate?
          3. How large is your team?
          4. Are there compliance requirements we need to consider?"

YOU:     "We value transparency. Yes, we have docs. 15 people. 
          We need ISO27001 compliance."

AI:      "Perfect. Based on transparency, I'd suggest:
          - Make CONSTITUTION.md a team working document
          - Create a clear governance folder for ISO27001
          - Add a public decision log in Decisions_ADR
          
          Does this align with how you want to work?"

YOU:     "Yes, but we also need to track vendor security reviews."

AI:      "Should we add 'Vendor_Security' subfolder under Governance, 
          or keep it in Knowledge_Base/Vendor_Intelligence? 
          What makes sense for your team?"
```

---

## Sharing with Your Team

**Email Template**:
```
Subject: Let's customize our workspace—I need your input

Hi team,

We're adopting a new organizational knowledge structure. I'm working with 
Copilot to customize it for us.

I need you to answer these questions by [DATE]:

1. What are our organizational values? (Top 3)
2. Which folders do you use most in your daily work?
3. What documentation frustrates you today?
4. What should we definitely NOT change?

Full structure preview: [README.md](README.md)

Reply with your thoughts, and we'll customize it together.
```

---

## Next Steps

1. **Choose which prompt version you want to use** (Full, Quick Start, or Phase-by-Phase)
2. **Gather basic info from your team**:
   - Organization name
   - Team size
   - Key values/principles
   - Compliance requirements
3. **Paste the prompt into your AI** (Copilot, ChatGPT, Claude, etc.)
4. **Follow the AI's questions** and provide clear answers
5. **Document customizations** as you go
6. **Share results** with your team for feedback

---

## Tips for Success

✅ **Be specific** with your answers—vague answers lead to vague results

✅ **Reference the constitution** during disagreements

✅ **Involve your team** early (don't customize alone)

✅ **Test with a pilot folder** before full adoption

✅ **Document everything** (changes, decisions, why you chose something)

✅ **Review quarterly** and update the constitution if needed

---

**Last Updated**: 2026-11-10  
**Status**: Ready to Use  
**Next Step**: Pick your prompt version and start the conversation!

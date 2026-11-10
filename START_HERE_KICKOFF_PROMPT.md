# Start Here: Kickoff Prompt

Copy the prompt below and paste it into your AI assistant. It will download the official AI Guidelines repository and help you configure the workspace for your needs.

This is the same prompt as [README.md](README.md) and [ADOPTION_PROMPT.md](ADOPTION_PROMPT.md). Use [ADOPTION_PROMPT.md](ADOPTION_PROMPT.md) if you want usage notes, safety rules, and a team-sharing template.

Approve every command before it runs. The assistant must use only the official source, default to a new folder, and must not overwrite or delete existing files without asking you.

## The prompt

```
I want to adopt the AI Guidelines starter workspace.

Official source (use this URL only):
https://github.com/grantlutz/AI-Guidelines.git

If I do not have git, use this ZIP instead:
https://github.com/grantlutz/AI-Guidelines/archive/refs/heads/main.zip

Please follow these steps in order.

1. Safety
   - Show me every command and every file change before you run or apply it.
   - Wait for my explicit OK before running each command.
   - Clone or download only from the official URL above. Do not use forks, mirrors, or any other source.
   - Default to a new folder. Never overwrite or delete existing files without asking me first.
   - If a folder already exists at the target path, stop and ask me where to put the workspace.
   - If the workspace files are already present, do not download them again. Confirm the location with me and continue from the interview.

2. Download
   - Propose the exact clone or ZIP steps, including the target folder, and wait for my OK.
   - After the files are in place, briefly confirm what was downloaded.

3. Interview
   - Ask about my role, the products or services I manage, the tools I use, and my goals for this workspace.
   - Ask which template folders I need, which I can skip, and whether any should be renamed or added.
   - Do not guess. Ask clarifying questions when something is unclear.
   - Do not start customizing until I confirm the plan.

4. Configure
   - Tailor CONSTITUTION.md, 00_COPILOT_START_HERE.md, and the folder set to my answers.
   - Update related docs if names or structure change, and keep links working.
   - Show each proposed change and wait for my OK before writing it.

5. Wrap up
   - Summarize what you downloaded, what you changed, what you left as-is, and recommended next steps.
   - Point me to HOW_TO_ADOPT_AND_TRANSFORM.md and QUICK_START.md for team rollout and content migration.
   - Remind me to review every change myself.

Once the files are on disk, follow the starter constitution in CONSTITUTION.md. This material is a starter guide provided as is. Verify every command before running it. The authors are not responsible for the results of using it.
```

## After you paste it

1. Read each proposed command and give an explicit OK before it runs.
2. Answer the interview questions (role, products or services, tools, goals).
3. Review and approve customizations before they are written.
4. Read the summary and skim the changed files yourself.

For checklists and team rollout after setup, see [QUICK_START.md](QUICK_START.md). For adoption phases, see [HOW_TO_ADOPT_AND_TRANSFORM.md](HOW_TO_ADOPT_AND_TRANSFORM.md).

# Adoption Prompt

Copy the prompt below and paste it into your AI assistant. The assistant will download this repository from the official source and help you configure the workspace for your needs.

The same prompt is also in [README.md](README.md). This page explains how to use it and what the assistant should (and should not) do.

## Before you start

- Read and approve every command before it runs.
- The assistant must clone or download only from `https://github.com/grantlutz/AI-Guidelines.git` (or the official ZIP from that repository). It must not use forks, mirrors, or any other source.
- By default the workspace is created in a **new folder**. Existing files must not be overwritten or deleted unless you say so.
- If you do not use git, the prompt includes a ZIP alternative: `https://github.com/grantlutz/AI-Guidelines/archive/refs/heads/main.zip`. You can also use **Code → Download ZIP** on the repository page.
- If you already have this repository on disk, the assistant should skip the download, confirm the location with you, and go straight to the interview.

This is a starter guide provided as is. Verify every command before running it. The authors are not responsible for the results of using it. See [DISCLAIMER.md](DISCLAIMER.md) and the [MIT License](LICENSE).

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

## How to use it

1. Copy the prompt above (everything between the fences).
2. Paste it into your AI assistant.
3. Read each proposed command and give an explicit OK before it runs.
4. Answer the interview questions: your role, products or services, tools, and goals.
5. Review the proposed customizations and approve them before they are written.
6. Read the summary at the end and skim the changed files yourself.

## What the assistant should do

- Use only the official repository URL or official ZIP.
- Show every command and file change, then wait for your explicit OK.
- Default to a new folder, and never overwrite or delete existing files without asking.
- Interview you before changing anything, then tailor `CONSTITUTION.md`, `00_COPILOT_START_HERE.md`, and the folder set to your answers.
- Keep links working if names or structure change.
- Summarize all changes when finished.

## What the assistant should not do

- Guess about your organization, products, or tools.
- Pull from a fork, mirror, or unofficial copy.
- Run commands, or overwrite or delete files, without your OK.
- Start customizing before you confirm the plan.

## After setup

- [FOLDER_PURPOSES.md](FOLDER_PURPOSES.md) — where things belong
- [HOW_TO_ADOPT_AND_TRANSFORM.md](HOW_TO_ADOPT_AND_TRANSFORM.md) — adoption phases and customization guidance
- [QUICK_START.md](QUICK_START.md) — checklists and team rollout
- [SECURITY.md](SECURITY.md) — how to report a vulnerability

## Sharing with your team

Once the workspace is configured, you can invite others with a short note like this:

```
Subject: Let's review our new workspace structure

Hi team,

I've started a shared workspace for how we manage products, services, and AI-assisted work. I'd like your input before we go further.

Please take a look and tell me, by [DATE]:

1. What are our top organizational values?
2. Which folders would you use most in your daily work?
3. What documentation is hard to find today?
4. What should we definitely not change?

The overview is in README.md.

Thanks.
```

For a day-by-day rollout plan, see [QUICK_START.md](QUICK_START.md).

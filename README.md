# AI Guidelines

A starter constitution and workspace template for managing products and services with AI assistants.

## Disclaimer

This repository is a **starter guide** provided **as is**, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement.

**Review and verify every command, script, and configuration before you run it.** Do not copy, execute, or apply anything from this guide until you have checked that it is appropriate for your environment and that you understand what it will do.

The authors and contributors are **not responsible** for any results, damages, or losses arising from use of this starter guide, whether from following its advice, running commands or scripts, applying configurations, or any other use or inability to use the material.

This material is **not legal, security, or compliance advice.** It does not create a professional relationship and does not replace review by qualified advisors for your organization, products, or services.

Not affiliated with or endorsed by any current or former employer of the authors.

All trademarks belong to their respective owners.

Use at your own risk.

This disclaimer is consistent with the [MIT License](LICENSE) included in this repository. The full text is also in [DISCLAIMER.md](DISCLAIMER.md). In the event of any conflict, the license terms control.

## About

This is a starter constitution and a set of guidelines you can turn into a working AI-assisted workspace for product and service management. It is a template, not a finished operating model: you (or your AI assistant, with your approval) adapt the principles, files, and folders to your work.

**Core files**

- [CONSTITUTION.md](CONSTITUTION.md) — principles for AI-assisted work and decision-making
- [00_COPILOT_START_HERE.md](00_COPILOT_START_HERE.md) — orientation and startup sequence for your AI assistant
- [ADOPTION_PROMPT.md](ADOPTION_PROMPT.md) — the get-started prompt and how to use it
- [FOLDER_PURPOSES.md](FOLDER_PURPOSES.md) — what each folder is for
- [HOW_TO_ADOPT_AND_TRANSFORM.md](HOW_TO_ADOPT_AND_TRANSFORM.md) — adoption phases and customization guidance
- [QUICK_START.md](QUICK_START.md) — checklists and team rollout
- [DISCLAIMER.md](DISCLAIMER.md), [LICENSE](LICENSE), and [SECURITY.md](SECURITY.md)

**Starter folders** (18): `Governance`, `Products`, `Playbooks`, `Knowledge_Base`, `Decisions_ADR`, `Engineering_Standards`, `Architecture_Repository`, `Coding`, `Incidents`, `Meeting_Notes`, `Project_Records`, `Executive_Communications`, `TPM_Toolkit`, `Templates`, `Company_Templates`, `Example_Work`, `Working`, and `Archive`. You do not have to keep all of them. See [FOLDER_PURPOSES.md](FOLDER_PURPOSES.md) for the full descriptions.

## Get started

Copy the prompt below and paste it into your AI assistant. The assistant will download this repository from the official source and help you configure it for your needs. Approve every command before it runs.

The same prompt, with more usage notes, is in [ADOPTION_PROMPT.md](ADOPTION_PROMPT.md).

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

## License

This project is licensed under the [MIT License](LICENSE). Copyright (c) 2026 Grant Lutz.

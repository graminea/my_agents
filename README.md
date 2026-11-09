# My Agents

Project instructions, implementation agents, and skills used to develop Text to ER.

## Use with Text to ER

Copy the following paths from `my_agents/text-to-er-Diagram/` into the root of your Text to ER checkout, preserving the directory structure.

| Path | Purpose |
| --- | --- |
| `AGENTS.md` | Project architecture, commands, and development rules |
| `.codex/agents/` | Implementer and reviewer agent definitions |
| `.agents/skills/` | Implementation and evaluation workflows |

Open the Text to ER checkout in a new Codex conversation. You can ask Codex to delegate a bounded change to `implementer` or request a read-only review from `reviewer`.

Update the files in this repository and copy them into the app checkout whenever they change. The app's Git ignore rules keep the installed copies local.

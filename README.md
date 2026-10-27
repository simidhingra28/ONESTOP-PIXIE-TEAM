# OneStop KWC Marketing Team

Claude Code agent team, visible as pixel characters via Pixel Agents. Synced through a private GitHub repo.

## First-time setup (Mushroom, once)
1. Install Claude Code (claude.com/claude-code), run `claude`, sign in.
2. Install VS Code 1.105+ and the **Pixel Agents** extension (pablodelucca).
3. Create an empty **private** GitHub repo called `onestop-marketing`.
4. Unzip this folder, open it in VS Code, open Pixel Agents, click **+ Agent**, and type:
   `Set this folder up as a git repo and push it to github.com/<you>/onestop-marketing.`

## Teammates (each person, once)
1. Install Claude Code, VS Code and Pixel Agents (steps 1–2 above).
2. Get added to the GitHub repo.
3. In a terminal: `claude`, then: `Clone github.com/<you>/onestop-marketing into my Documents folder.`
4. Open that folder in VS Code, Pixel Agents, **+ Agent**.

## Daily use
- The Marketing Lead pulls the latest files when it starts and pushes after every change.
- To change rules or facts, just ask it ("add $149 gutter clean to company.md"). It shows the change, you approve, it pushes.
- Changes to agents take effect next time you click **+ Agent**.

## Private by design
`board/inputs/` (customer lists, job photos) is never pushed to GitHub. Each person keeps their own copy locally.

## Folders
- `CLAUDE.md` — Marketing Lead instructions
- `context/` — company facts + brand rules
- `.claude/agents/` — seo, social media, customer reachout, commercial relations leads
- `board/` — goals, inputs (local only), briefs, outputs, reports, approval queue

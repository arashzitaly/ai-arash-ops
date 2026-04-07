# Notion Workflow Decisions Baseline
Last synced: 2026-04-07
Purpose: Durable decisions harvested from Notion and codified for repo operations.

## Sources
- Second Brain Operating Rules
  - https://www.notion.so/32b875ec8f1b8145a2bbfa3871b757ec
- Second Brain Sync Schema (historical, archived)
  - https://www.notion.so/32b875ec8f1b81f181e1db988fe3a571
- Obsidian + Notion Knowledge Architecture
  - https://www.notion.so/32c875ec8f1b81eab0abc72953552e3b
- Custom Instruction - Codex (Second Brain Write Policy)
  - https://www.notion.so/32e875ec8f1b812fb1f7e231fc6dcdf0
- Custom Instruction - ChatGPT (Second Brain + Obsidian)
  - https://www.notion.so/32e875ec8f1b816da5fcdf2944f7b4eb

## Canonical decisions
1. Second Brain is the canonical long-term store for durable operational knowledge.
2. Obsidian is the destination for ideas, research, concepts, and synthesis.
3. Never split the same content across both databases.
4. Use update-first behavior:
   - prefer DISCARD over weak storage
   - prefer UPDATE over CREATE
   - prefer MERGE over fragmentation
5. Never auto-save; require explicit confirmation before write.
6. Use fixed field contract for Second Brain writes (see `AGENTS.md`).
7. Follow deterministic Obsidian link topology for non-exempt HiveBox notes:
   - include `[[HiveBox Project]]`
   - include `[[Roadmap Index]]`
   - exemptions: Formula 1 notes, Volvo internship note, templates

## Standard operating flow
`Extract -> Route -> Quick check -> Codex insert/update`

## Notes
- The former "Second Brain Sync Schema" page is archived and superseded by "Second Brain Operating Rules".
- This file is a baseline reference. `AGENTS.md` remains the execution contract.

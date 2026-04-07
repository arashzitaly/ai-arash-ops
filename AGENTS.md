# AGENTS.md
Version: 2026-04-07.2
Scope: Cross-device operating policy for AI-assisted knowledge capture and Notion mutation.

## Canonical routing
- Use `🧠 Second Brain` for durable operational knowledge:
  - decisions
  - preferences
  - rules
  - constraints
  - stable workflows
  - stable project conclusions
  - reusable reference context
- Use `💎 Obsidian` for:
  - ideas
  - research
  - concepts
  - synthesis
  - exploratory thinking
- Never split the same content across both databases.
- If destination is ambiguous, do not write.

## Do not store
- raw transcript text
- casual chat
- temporary task chatter
- brainstorming fragments not yet durable
- duplicate restatements
- narrow notes that belong inside broader canonical pages

## Mandatory pre-write sequence
1. Search target database for canonical destination candidates.
2. Choose exactly one action:
   - `DISCARD`
   - `UPDATE` existing canonical entry
   - `MERGE` into broader canonical entry
   - `CREATE` new canonical entry
3. Priority:
   - prefer `DISCARD` over weak storage
   - prefer `UPDATE` over `CREATE`
   - prefer `MERGE` over fragmentation
4. Never auto-save unless explicitly requested.
5. Before writing, ask exactly:
   - `Worth saving to Second Brain — confirm?`

## Decision rules
- `UPDATE`: content strengthens or extends an existing canonical item.
- `MERGE`: content is too narrow and fits a broader canonical page.
- `CREATE`: only when no strong canonical destination exists and content is clearly reusable.
- `DISCARD`: content is weak, temporary, repetitive, unclear, or non-durable.

## Writing rules
- Use existing database schema only. No schema changes.
- Keep entries concise, durable, normalized.
- Do not preserve conversational wording.
- Distill to:
  - decision
  - reasoning
  - impact
  - next action
- Keep titles short, canonical, reusable.
- Preserve continuity; avoid unnecessary rewrites.

## Mutation boundaries
- No schema, view, filter, or sort changes unless explicitly requested.
- No deletions unless explicitly requested.
- Do not edit unrelated Notion content.
- If uncertain, stop and report instead of writing.

## Output requirement before any write
Always show:
- Classification
- Why durable or not durable
- Recommended destination
- Update / Merge / Create / Discard
- Candidate title
- Candidate summary

## Workflow contract
- Operating flow: `Extract -> Route -> Quick check -> Codex insert/update`.
- Classifier stage:
  - classify as `Notion`, `Obsidian`, or `Discard`
  - propose `Update/Merge/Create/Discard`
- Mutation stage:
  - re-check destination
  - search for duplicates
  - write only after explicit confirmation
  - keep summaries compressed

## Canonical fields for Second Brain writes
- Title
- Category
- Type
- Status
- Area
- Importance
- Stable Memory
- Summary
- Canonical Note
- Next Action
- Related To
- Source
- Review Date

## Obsidian graph rule
- For non-exempt HiveBox notes, keep deterministic links to:
  - `[[HiveBox Project]]`
  - `[[Roadmap Index]]`
- Exemptions:
  - Formula 1 notes
  - Volvo internship note
  - templates

## Local overrides
- If `AGENTS.local.md` exists in the active workspace, apply it after this file.
- `AGENTS.local.md` may define machine-specific paths or local automation details.
- Local overrides must not weaken routing or durability rules in this file.

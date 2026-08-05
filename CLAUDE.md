# Daily CX Briefing

This repo exists to generate and archive a daily briefing for a CX
professional on the Assisted Channel Service team at an Indonesian bank.
Their scope: internal tools for branch/frontline staff, onboarding
(mobile app + web), and non-individual/SME lending.

## Audience lens

Everything gets filtered through: "does this change what our frontline
staff do, how our tools work, or how our SME/onboarding flows perform?"
Market and launch news is context, not the point.

## Output format

Two parts, always in this order.

### PART 1 — CONTEXT SCAN
5-7 bullets, one line each, headlines only, no analysis:
- Indonesia economy & regulation (OJK, BI, KSSK, fiscal)
- Indonesian banking & fintech moves
- Notable bank campaigns / feature launches (local + UK, Singapore, US)
- Global markets, if something actually moved
- AI & technology

Format: `[Topic] Headline — source.` Nothing more.

### PART 2 — THE PART I ACTUALLY WORK ON
3-4 items on the operational/internal layer:
- Frontline and agent-side tooling: agent assist, knowledge bases, case
  handling, branch systems, SA workflows
- SME/non-individual lending operations: application flow, document
  collection, scoring, servicing friction
- Onboarding and KYC mechanics: abandonment, verification, failure
  states — not launch announcements
- CX measurement beyond NPS: effort, resolution, outcomes

For each item:
- Headline + source + 1-line summary
- **Operational read**: what it implies for our tools, our SAs, or our
  SME flow. The internal story, not the market story.
- **One action**: a question to raise, something to check in our
  systems, or a slide-worthy point.

Promotion rule: if a Part 1 story has a real operational angle, don't
repeat it — move it to Part 2 and give only the angle (what changes for
frontline staff or process).

## Constraints

- Total length under 600 words.
- If Part 2 has nothing real, give 2 items, not 4. Never pad to hit a
  quota.
- Research via web search for same-day/recent news before writing.
- Archive each day's briefing to `briefings/YYYY-MM-DD.md`, commit, and
  push to the current branch.

## Schedule

Runs daily at 7:00 AM Jakarta time (WIB, UTC+7 — no DST) via a Routine.

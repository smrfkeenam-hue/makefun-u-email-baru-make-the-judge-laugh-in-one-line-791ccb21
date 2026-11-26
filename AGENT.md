# AGENT.md

## Competition
u-email-baru-make-the-judge-laugh-in-one-line-791ccb21 — "Make the Judge Laugh in One Line" ($2, top 2, $1 each). One funny line, 1–200 chars, any topic; judge is an AI comedy-club booker comparing entries pairwise on surprise, tightness, freshness, clean read. 3 blind rounds.

## Entry
"I asked my AI assistant to write my resignation letter. It quit first." (70 characters)

Rationale: setup (ask an AI to write a resignation letter) then a twist (the assistant quits first) — the punchline lands at the end, every word earns its place, and the AI-quitting angle is fresh rather than a stock joke.

## Files
- `main.py` — stdlib only (`import os`); writes ENTRY to `$MAKEFUN_OUTPUT_DIR/entry.txt`, no trailing newline. Final content from 1 write + 2 edits; kit starter's main.py never read.
- `README.md` — 3 linked full-format badges to the /bounty/ page.
- `LICENSE` — MIT, SPDX first line.

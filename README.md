# IT Asset Inventory — Problem to PRD

> **Branch:** `skill/problem-to-prd`
> **Skills:** R1 · R6 · A3 · W1 · F1
> **Audience:** PM · Eng

---

## For the Facilitator

### Session Overview

| | |
|---|---|
| **Kata** | 1: IT Asset Inventory |
| **Session** | Problem to PRD |
| **Skills** | R1 · R6 · A3 · W1 · F1 |
| **Duration** | 2 hours (facilitated) + self-directed extension |
| **Slide Deck** | https://gamma.app/docs/efkgw26bdjm41wm |
| **Miro Board** | https://miro.com/app/board/uXjVG8QDVG4%3D/ |

### Session Timing

| Time | Activity |
|------|----------|
| 0:00–0:15 | Concept framing — open the Gamma slide deck and walk through each slide |
| 0:15–0:30 | Orient to Miro board + this starting state |
| 0:30–1:05 | Step 1 exercise (Miro — Context frame) |
| 1:05–1:25 | Step 2 exercise (Miro — Exercise frame) |
| 1:25–1:30 | Step 3 wrap-up |
| 1:30–1:50 | Debrief — use Miro Debrief frame prompts |
| 1:50–2:00 | Extension brief — point to Extension Zone in Miro |

### What to Watch For

- Teams jumping to solution before writing a problem statement — slow them down
- PRDs that list features without success metrics — push for measurable outcomes
- Assuming the spreadsheet is the problem (it's a symptom) — probe deeper

### Facilitation Tips

- Start with "What breaks when the spreadsheet is wrong?" to surface real pain
- Enforce: no solution-first thinking until the problem statement is approved by the group
- Compare PRDs at debrief — project 2 side by side and ask: which one would an engineer trust?

### Extension / Coaching Office Hours

Participants can continue extension work independently and bring it to **Coaching Office Hours**.
At Office Hours, focus on: what decision did they make, why, and what would they change?

---

## For Participants (Developer · PM · UX)

### Getting Started

```bash
git clone https://github.com/DyingPoets/kata-asset-inventory
git checkout skill/problem-to-prd
```

Open the Miro board and the Gamma slide deck — have both visible during the session.

- **Slides:** https://gamma.app/docs/efkgw26bdjm41wm
- **Miro Board:** https://miro.com/app/board/uXjVG8QDVG4%3D/

### What You'll Practice

- R1
- R6
- A3
- W1
- F1

### Your Starting State

You have two files:
- `interviews/stakeholder-transcript.md` — a real-feeling interview with the ops manager
- `data/assets-export.csv` — a messy 3-tab CSV with duplicates and missing fields

Your goal: write a production-quality PRD using the 8090 Software Factory.

### Step by Step

**Step 1:** Read the interview transcript and the CSV. Write a 2-sentence problem statement. Use: *[User] needs [outcome] because [context]. Today they [workaround].*

**Step 2:** Generate a PRD using the 8090 Software Factory. Must include: goals, non-goals, 3+ user stories, success metrics.

**Step 3:** Compare your PRD to `solutions/asset-inventory-prd.md`. List 3 things you'd change.

### What Good Looks Like

A PRD where an engineer could start building without asking a single clarifying question. Success metrics are specific numbers, not adjectives.

See the `solutions/` directory for reference examples — but try the exercise first.

### Extension Work

- Add a data model section: entities, fields, relationships for Asset, Location, Owner
- Write BDD acceptance criteria for the 3 highest-priority user stories
- Rewrite the problem statement for the CFO audience (cost-focused, not ops-focused)

Bring your extension work to **Coaching Office Hours**. You'll get 15 minutes of focused feedback.

---

Part of the [PDLC Training Katas](https://github.com/DyingPoets) series.

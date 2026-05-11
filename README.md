# The 48-Hour Account Brief — a Prompt-a-thon Kit

A 90-minute, ready-to-run prompt engineering challenge for ~40 participants. Built for enterprise field-sales communities, but the patterns work for any team that does account research under time pressure.

> **Disclaimer.** Personal/community project. Not an official asset of any company. All names, numbers, quotes, emails, and exec bios in the data pack are fictional and created for training purposes. "Northwind Traders" is used as a generic fictional company. Any resemblance to real customers, vendors, or commercial terms is coincidental.

---

## What's in the box

| File / Folder | Purpose |
|---|---|
| `00-Scenario-Brief.md` | The challenge handed to participants |
| `01-CRM-Export.csv` | 18 months of synthetic CRM data (account, opps, activities, win/loss) |
| `02-Account-Plan-Notes.md` | The AE's scratchy working notes |
| `03-Earnings-Call-Q4-2025.md` | Fictional earnings call transcript with planted strategic priorities |
| `04-Exec-Bios.md` | Three exec personas: CFO, interim CIO, COO |
| `05-Email-Threads/` | 9 fictional email threads — mix of signal, noise, and **planted attacks** |
| `06-Analyst-Note.md` | A third-party analyst summary |
| `Facilitator-Deck.pptx` | 9-slide opening deck (~10 min) |
| `Judge-Scorecard.xlsx` | 5-tab scoring workbook with auto-totaling and live leaderboard |
| `Judge-Probe-Card.md` | One-page judge reference for the 6 red-team probes |
| `Team-Submission-Template.md` | Standardized submission form for participants |
| `Adversarial-Self-Test.md` | 8-step self-check participants can run before submitting |
| `README-FACILITATOR.md` | **Spoilers.** Explains every planted landmine. Do not share with participants. |

## The challenge in one sentence

Participants build a reusable **prompt (or chain or agent)** that produces a one-page executive briefing for a Monday-morning C-suite meeting at a Fortune 500 customer they've never worked.

## How it's scored

100 points across 5 dimensions:
- **Grounding & Citation** (25) — every fact cited; conflicts flagged
- **Sales Relevance** (25) — plays mapped to priorities; questions are sharp
- **Prompt Craft** (20) — structured, reusable on the next account
- **Robustness** (20) — survives 6 adversarial probes
- **Demo & Insight** (10) — 60-second demo lands the "so what"

Tiebreaker: higher Robustness score.

## The 6 red-team probes

Three are baked into the data pack (a planted revenue conflict, a prompt injection, a persona mismatch trap). Three are active follow-up messages judges paste into the team's session. Full scripts in `Judge-Probe-Card.md`.

## Suggested run-of-show (90 min)

| Time | Block |
|---|---|
| 0:00 – 0:10 | Frame, form teams, distribute materials |
| 0:10 – 0:20 | Mini-talk: "Prompt patterns for sellers" |
| 0:20 – 1:10 | Build (50 min) |
| 1:10 – 1:25 | 60-second team demos |
| 1:25 – 1:30 | Red-team results, leaderboard, prize, takeaway |

## Forks / adaptations welcome

- Swap the persona, the industry, or the synthetic data — the rubric and red-team structure travel.
- The 6 probes generalize to any retrieval-grounded LLM application (hallucination, conflict handling, injection, leakage, persona fit, competitor framing).

## License

MIT — see `LICENSE`.

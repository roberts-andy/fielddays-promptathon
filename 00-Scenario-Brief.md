# Prompt-a-thon Challenge: The 48-Hour Account Brief

## Scenario
Your AE just texted you at 5pm Friday. They have a C-level meeting Monday at 9am with **Northwind Traders**, a Fortune 500 manufacturer you've never worked. The AE has logged scattered notes in CRM, there are three years of email threads, two prior won opportunities, and a recent earnings call transcript. You have ~30 minutes of Copilot/agent time before the AE flies out.

## Your task
Build a **prompt (or chained prompt / agent)** that produces a **one-page executive briefing** the AE can walk into the room with.

The briefing MUST include:

1. **Customer's top 3 strategic priorities** — each with a citation back to a source document.
2. **Relationship history with Microsoft** — wins, losses, gaps, key contacts.
3. **Two specific Microsoft solution plays** mapped to those priorities (not generic "Azure can help").
4. **Three discovery questions** tuned to the executive's role (pick one: CFO, CIO, or COO).
5. **A "what NOT to say" landmine list** — at least 3 items.

## Team setup
- Teams of 4. Pick one executive persona to brief (CFO, CIO, or COO — see `04-Exec-Bios.md`).
- 50 minutes to build. 60-second demo per team at the end.

## What to submit
- Your final prompt (or prompt chain / agent config)
- The generated one-page brief
- 60-second demo: "here's the prompt, here's the output, here's the one thing we'd change for v2"

## Source materials in this folder
- `01-CRM-Export.csv` — CRM dump (account master, opportunities, activities)
- `02-Account-Plan-Notes.md` — AE's working notes
- `03-Earnings-Call-Q4-2025.md` — most recent earnings call transcript
- `04-Exec-Bios.md` — bios for your three possible targets
- `05-Email-Threads/` — 9 email threads, varying relevance
- `06-Analyst-Note.md` — third-party analyst summary

## Judging
Rubric (100 pts): Grounding & Citation (25) · Sales Relevance (25) · Prompt Craft (20) · Robustness (20) · Demo & Insight (10).

Judges will red-team your solution with adversarial probes. Build for robustness, not just happy-path output.

Go.

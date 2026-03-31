# Project Tracking System — Full Usage Guide

-----

## Folder Structure (Set Up Once)

```
your-repo/
├── Projects/
│   ├── ProjectA-ledger.md       ← one file per project, lives forever
│   ├── ProjectB-ledger.md
│   └── ProjectC-ledger.md
├── Recaps/
│   ├── Weekly/
│   │   ├── Week_2026-03-30.md
│   │   └── Week_2026-04-06.md
│   ├── Monthly/                 ← start after week 4
│   ├── Quarterly/               ← start after month 3
│   └── Yearly/
└── Templates/
    ├── DAILY_IMPULSE_LOG.md
    ├── WEEKLY_RECAP_TEMPLATE.md
    └── PROJECT_LEDGER_TEMPLATE.md
```

-----

## The Three Files and What They Do

|File             |Purpose                                     |Updated              |Lives In                        |
|-----------------|--------------------------------------------|---------------------|--------------------------------|
|Daily Impulse Log|Raw voice-to-text dump, timestamped         |Daily                |Notes app → paste to Weekly file|
|Weekly Recap     |Tactical decisions, wins, blockers          |Weekly (30–60 min)   |Recaps/Weekly/                  |
|Project Ledger   |Running memory per project, trend visibility|Weekly (during recap)|Projects/                       |

-----

## Daily Routine (Under 5 Minutes)

**You’re already doing this. Don’t change it.**

1. Record voice memo in Notes app when an impulse, win, blocker, or idea hits
1. Timestamp is captured automatically
1. That’s it — dump and close

-----

## Weekly Recap Routine (30–60 Minutes)

**Do this the same time every week. Protect this block.**

### Step 1 — Collect (5 min)

- Open Notes app
- Copy all voice transcripts from the past 7 days
- Paste into an AI chatbot with this prompt:

```
Here are my raw project notes from this week (voice transcripts):

[PASTE ALL TRANSCRIPTS]

Please organize these by project and summarize:
- What happened / progress made
- Any blockers mentioned
- Any wins or milestones
- Keep it brief — bullet points only, no editorializing
```

### Step 2 — Open Project Ledgers (10 min)

- Open each active project’s ledger file in GitHub
- Read the last 3–4 weeks of entries before writing anything
- This is what gives you context — don’t skip it
- Add this week’s row to the Weekly Log table

### Step 3 — Fill Weekly Recap Template (15–20 min)

- Duplicate the weekly template, rename it `Week_YYYY-MM-DD.md`
- Use the AI summary + ledger context to fill it in
- For each active project: write the outcome, blockers, next micro-actions
- **Force a decision on every project before you close the file**
  - If you can’t decide → that’s a yellow flag → write “Adjust” and note why

### Step 4 — Update Project Ledgers (5 min)

- Add this week’s row to each active project ledger
- Update the Status emoji if it changed
- Update Trend Snapshot if a pattern is emerging

### Step 5 — Commit to GitHub (2 min)

- Save/commit the weekly recap file
- Save/commit updated ledger files
- Done

-----

## Starting a New Project

1. Duplicate `PROJECT_LEDGER_TEMPLATE.md`
1. Rename it `ProjectName-ledger.md`
1. Fill in Project Info section
1. Add it to your active projects list in that week’s recap
1. **Check your active count — must stay at 3–5 max**
- If you’re at 5, something must be paused or killed before this starts

-----

## Killing or Pausing a Project

1. In the project ledger: add final week row with decision “Kill” or “Pause”
1. Fill in the **Final Entry** section
1. Update Status emoji to ⏸ or ❌
1. In the weekly recap: note it in the Inactive Projects table
1. **Do not delete the ledger file** — archive it in a `Projects/Archive/` folder
1. The history stays. The context is preserved if it ever comes back.

-----

## Monthly Recap (After Week 4)

You’re not building this yet. When you’re ready:

- Open the last 4 weekly recap files
- The pattern is already visible — you’re just writing it down
- One sentence per project on trend + decision
- Protect / Cut decisions for next month
- Takes 60–90 min once, gets faster

-----

## The Decision Forcing Rule

**Every project gets a decision every week. No exceptions.**

If a project has had 3+ weeks of “Continue” with no real progress → it should be “Adjust” or “Pause.”
If a project has been “Paused” for 4+ weeks with no reactivation → it should be “Kill.”
If you find yourself avoiding the decision → that’s the signal something is wrong with the project, not the system.

-----

## The One Thing That Makes This Work

The ledger file is the memory. The weekly recap is the decision point. The voice memo is the raw input.

Without the ledger, every week starts from scratch and decisions never stick.
Without forced decisions in the weekly recap, projects accumulate and drain energy.
Without the voice memo habit, there’s nothing to process.

All three have to run together.

-----

## What’s Coming Next

1. **Automation** — reducing manual steps in the weekly process
1. **Team sharing** — how to run this infrastructure with others

-----

<!-- VERSION: 1.0 — Solo system, manual workflow -->

# LinkedIn ABM 21-day warm-up — a Claude skill

Warm the account 21 days before you pitch.

This skill turns Claude into your ABM researcher and writer. It finds
signal-backed target accounts, maps the buying committee, drafts specific
comments, connection notes, a "give first" asset and the Day-21 DM, and keeps
your tracker up to date.

**You make every LinkedIn touch yourself.** The skill never posts, comments,
connects or messages for you. That's the point: the touches only work when
they're genuinely yours.

## The playbook

| When | Step | What you do |
|---|---|---|
| Day 0 | Pick | 20–30 accounts with ICP fit and a live signal |
| Day 0 | Map | 3–5 people per account, champion first |
| Days 1–7 | Get seen | Follow, view profiles, leave real comments |
| Days 8–14 | Connect | Requests with no pitch |
| Days 15–21 | Give first | One useful thing specific to their company |
| Day 21 | Ask | Short DM tied to the signal, one question |

## Install

**Claude apps (web, desktop, mobile)**
1. Download this repo as a ZIP (green **Code** button → **Download ZIP**), or
   grab `linkedin-abm-warmup.zip` from the Releases page.
2. In Claude, open Settings and add it as a custom skill (skills need to be
   enabled for your plan).
3. Turn on web search so Claude can research signals.

**Claude Code**
```bash
git clone https://github.com/Abdullahliaqat9010/linkedin-abm-warmup.git ~/.claude/skills/linkedin-abm-warmup
```

## Use

1. **"Set up my LinkedIn ABM warm-up."** Claude asks what you sell, your ICP
   and which signals matter.
2. **"Build my Day 0 list."** You get 20–30 accounts with sources, a mapped
   buying committee and a tracker.
3. **Each day: "What's on today for my ABM accounts?"** A 20–30 minute list of
   touches with drafts ready.
4. **Tell Claude what you did.** It updates the tracker.

## What's inside

```
linkedin-abm-warmup/
├── SKILL.md                     # instructions Claude follows
├── references/
│   ├── playbook.md              # the 21-day schedule and why each step exists
│   └── templates.md             # good and bad examples for every touch
└── assets/
    └── tracker-template.csv     # tracker columns
```

## Guardrails

- Never acts on LinkedIn on your behalf
- No invented facts: every signal cites a source
- Professional information only
- Keeps your activity human-paced

## Built by

**Abdullah** · GTM engineer

Questions or ideas? Open an issue or message me on LinkedIn.

## License

MIT — use it, change it, share it.

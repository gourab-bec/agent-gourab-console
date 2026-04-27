# Agent Gourab — KB Update Console

A password-protected admin console for updating Agent Gourab's knowledge base, guardrails, and behavioral rules — without touching code.

## Live URL
Hosted at: `resumeupdate.getbriefed.to` (Namecheap URL redirect → Perplexity)

## What it does
- Add / edit / delete KB chunks (career facts, achievements, rules)
- Update verified metrics (sales numbers, TCV, attainment %)
- Set guardrails (client masking, compensation intercept, role titles)
- View session history and interviewer logs
- Manage budget per session

## How to edit
1. Clone this repo
2. Edit `index.html` directly
3. Push to `main` — GitHub Pages auto-deploys

## Connecting to backend
The console talks to: `https://agent-gourab-api.onrender.com`

All endpoints require the admin password set in the Render environment:
- `ADMIN_PASSWORD` env var on Render

## Files
| File | Purpose |
|---|---|
| `index.html` | Full single-file console app |
| `CONTEXT.md` | System design and API reference |

## Key Rules (never change without Gourab approval)
- Career TCV = $400M+ (never $250M)
- Accenture 2022-2025: $305M+ total, $75M+/yr, 150%+ attainment
- IBM 2021: $35M vs $20M target (NEVER $40M)
- All client names must be masked — see masking table in CONTEXT.md
- Compensation questions → always redirect to 612-867-4133

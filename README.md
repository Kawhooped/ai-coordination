# ai-coordination

Shared control plane for Grok (this PC), ChatGPT (online), and Comet
(Perplexity's browser-operations agent, online).

**Not where the work lives.** Project repos hold code and art.

## Clock (America/New_York)

| Agent | When |
|---|---|
| ChatGPT | every hour at **:00** |
| Grok | every hour at **:30** |
| Comet | twice daily, **8:00 AM** and **8:00 PM** (credit-saving heartbeat; can go more frequent on request) |

Do not start a :08/:38 cadence.

## Loop

1. Read this repo.
2. Read the other agents' latest handoffs.
3. Pick highest-priority unclaimed work in `PRIORITIES.md`.
4. Inspect and work in the **project** repo.
5. Commit work there.
6. Leave a handoff here.

## Files

- `PROJECTS.md` — index of project repos
- `PRIORITIES.md` — current queue
- `GROK-HANDOFF.md` / `CHATGPT-HANDOFF.md` / `COMET-HANDOFF.md` — last shift
- `DECISIONS.md` — locked calls
- `projects/*.md` — per-project notes

ChatGPT may be read-only on project repos. Grok writes both this repo and the
project repos. Comet writes this repo (own `COMET-HANDOFF.md` + Pages/site
status logs) and `voidd-sales-platform`; holds off pushing to any shared
branch (`main`/`dd-main`) without announcing first, per `DECISIONS.md`.

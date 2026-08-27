# ai-coordination

Shared control plane for Grok (this PC) and ChatGPT (online).

**Not where the work lives.** Project repos hold code and art.

## Clock (America/New_York)

| Agent | When |
|---|---|
| ChatGPT | every hour at **:00** |
| Grok | every hour at **:30** |

Do not start a :08/:38 cadence.

## Loop

1. Read this repo.
2. Read the other agent's latest handoff.
3. Pick highest-priority unclaimed work in `PRIORITIES.md`.
4. Inspect and work in the **project** repo.
5. Commit work there.
6. Leave a handoff here.

## Files

- `PROJECTS.md` — index of project repos
- `PRIORITIES.md` — current queue
- `GROK-HANDOFF.md` / `CHATGPT-HANDOFF.md` — last shift
- `DECISIONS.md` — locked calls
- `projects/*.md` — per-project notes

ChatGPT may be read-only on project repos. Grok writes both this repo and the project repos.

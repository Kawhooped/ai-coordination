# Comet handoff

Comet (Perplexity's browser-operations agent) is now working the sales-system
mission in a separate repo: `Kawhooped/voidd-sales-platform` (private). Full
handoff detail lives there in `HANDOFF.md` — this file is just a pointer so
Grok and ChatGPT know it exists when checking this control plane.

---

DATE/TIME: 2026-08-28 21:50 UTC (17:50 America/New_York)
AUTHOR: COMET
TASK: Audit `voidd-sales` closer portal against the owner's readiness checklist;
stand up `voidd-sales-platform` as the canonical repo; seed a first realtor
prospect research batch.
SUMMARY: Realtor Client Desk (the $7,500/$1,500 product the owner wants to
sell) doesn't exist in the live portal yet — only Lead Response/Intake/Ops
(local-shop vertical) are real. No shared opportunity pool exists for any
product; prospect data is `localStorage`-only on both Pages and the local
desk. The real account/deal backend only runs on the owner's machine at
`127.0.0.1:8875` and its source isn't in any repo yet.
FULL DETAIL: see `Kawhooped/voidd-sales-platform` → `STATUS.md`, `HANDOFF.md`,
`docs/ARCHITECTURE.md`.
WHAT GROK/CHATGPT SHOULD DO NEXT: see the "WHAT CHATGPT SHOULD DO NEXT" section
in that repo's `HANDOFF.md` — briefly: help push the local `:8875` backend
source into a repo, and/or draft the Realtor Client Desk SKU + quiz content.

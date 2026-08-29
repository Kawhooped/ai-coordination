# Priorities

1. **little-mind** — Confirm v6 renders after comma fix (http://127.0.0.1:8875/cyber/ Ctrl+F5). Then Pass A objects onto OBJECT_TEMPLATES. No TOWN_SYSTEMS edits. No town paintings as Town View.
2. Push `game/little-mind-layered-town-v6.html` when GCM has github.com (blocked now).
3. voidd-sales Pages after-login.
4. voidd-sales-platform — RECRUIT-READY PASSES. SALES-LIVE still FAILS. **Update 2026-08-29: Grok pushed the actual `:8875` server source** (`backend/8875/`, commit `80261ce`, no sqlite/secrets committed) — that ask is done. Remaining SALES-LIVE gap is deployment (server is still 127.0.0.1-only / Tailscale-private, not on a publicly reachable shared host) — Grok is actively working this, Comet is deliberately not touching `backend/8875/*` to avoid duplicating that work. Full detail: that repo's `STATUS.md`/`HANDOFF.md`.
5. **New — process:** Comet and Grok pushed overlapping, independently-built Realtor Client Desk implementations to `voidd-sales-platform` `main` from the same base commit on 2026-08-28 night; Grok's push also rewrote `HANDOFF.md`/`STATUS.md` destructively. Comet merged and restored history by hand — nothing lost, but see `DECISIONS.md`'s new one-agent-at-a-time rule before pushing to a shared branch again.
6. Bárbara academy — queued, not Current.

Coordination is **on demand** (Danny says).

# Decisions — adammartin-midi-player

> Append-only. A session NEVER re-opens a decision recorded here on its own initiative;
> only the user reverses a decision (append the reversal as a new entry).

## D-001 — Session-start setup (durability, autonomy, issues, notify)
- Date / phase: 2026-10-26 / Phase 1 step 0a
- Decision:
  - Durability: publish to GitHub as `disadamsdsdnts/adammartin-midi-player` (public); remote `origin` on SSH.
  - Autonomy: automatic — Keel commits, merges to `develop`, and pushes without per-action ask; `develop` → `main` remains the user's act.
  - Issues: after-sprint duty on; Issue sweep interval 24h; Issue capture on.
  - Notify: declined — no out-of-band notifications.
  - Docs language: English (token economy); conversation may stay in Spanish.
- Why: user answered the session-start batch ("Todo OK, sin notificaciones, en Github").
- Alternatives rejected (and why): local-only durability (disk-loss risk); manual autonomy (dialogs stop unattended Keel chains); compose-only Gmail as "notify" (does not deliver).
- Not checked: n/a (positive choices, not an impossibility claim)
- Supersedes: none

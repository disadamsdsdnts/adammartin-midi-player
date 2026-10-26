# Keel conformance — adammartin-midi-player

> Sweep of `MANIFEST.md` Table 1 at Phase 1 step 0a. States: `present` / `missing` / `declined` / `n/a`.
> Authorised sources: disk, MANIFEST.md, docs/decisions.md — never a previous sweep.

| Requirement | State | Notes |
|---|---|---|
| `docs/PROGRESS.md` | present | |
| `docs/decisions.md` | present | |
| `docs/lessons-learned.md` | present | |
| `docs/sessions.md` | present | |
| `scripts/keel-time` | present | copied from sibling project; will regenerate if contract drifts |
| `scripts/keel-clock` | present | byte copy of skill `keel_clock.py` |
| `docs/.keel/clock.jsonl` | present (gitignored) | created on first `keel-time start` |
| Off-machine durability | present | origin → github.com/disadamsdsdnts/adammartin-midi-player — D-001 |
| Clean working tree at block close | present | process rule |
| `CLAUDE.md` + `AGENTS.md` lock | present | KEEL:BEGIN v7.3.2 |
| `GEMINI.md` / `.gemini/settings.json` | n/a | Gemini CLI not chosen yet |
| Embedded skill trees | missing | awaiting user answer (Phase 1 0a) |
| `docs/00-competitive-landscape.md` | missing | Phase 1 step 0 |
| `docs/01-discovery.md` | missing | Phase 1 |
| `docs/estimate.md` | missing | Phase 1 close |
| `docs/token-ledger.md` | missing | Phase 1 close |
| Phase 2+ artifacts | missing | later phases |
| Parallel / chaining / playground / verify scripts | n/a or missing | condition-gated; scaffold at Phase 5 unless card requires earlier |

Last sweep: 2026-10-26 — Phase 1 step 0a

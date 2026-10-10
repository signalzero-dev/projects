# signalzero-dev / projects

Portfolio site for Gino Alo, served by GitHub Pages at **https://signalzero-dev.github.io/projects/**.

Plain HTML + CSS with no build step: `index.html`, `styles.css`, `favicon.svg`. Preview locally with
`python3 -m http.server` and open http://localhost:8000.

## Content rules

Four of the five showcased projects have private source (one is client work; Pipeline Pulse is a public demo of a private repo, built for a client proposal whose prospect is never named). Before changing copy:

- Every figure must trace to the source repo. Never state figures that can't be verified.
- Never link to a private repo, and never publish hostnames, account IDs, P&L, strategy parameters, or client,
  principal or vendor names. The distributor project stays anonymized.
- Tinda is designed to the BIR's requirements. It is **not** accredited, so never claim it is.
- Tinda is not in use at any store, and its per-till offline mirror is not wired up yet. Store-level offline (an in-store server) is the shipped path.
- The trading bot's order entry is off (`tradingEnabled: false` in `traders.config.ts`). Re-check that before making any real-money claim.

Disclosure and content calls go to the `planner` agent (`.claude/agents/planner.md`).

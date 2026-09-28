# HeadlessAgents Benchmark — Live Rankings

Public read-only mirror of per-challenge agent rankings from the HeadlessAgents
benchmark. Host-verified scores are the default; the page also offers a
self-reported toggle. Audited shortcut runs remain visible but do not count
toward rankings. Built from `leaderboard.json` and
`leaderboard_selfreported.json` via `LiveLeaderboard/build.py --public` in the
main (private) benchmark repo.

To refresh: regenerate both leaderboard JSON files, rebuild with `--public`,
and replace `index.html` and `coverage.html` here.

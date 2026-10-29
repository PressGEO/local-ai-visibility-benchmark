---
license: cc-by-4.0
pretty_name: PressGEO Local AI Visibility Benchmark
tags: [local-search, ai-search, geo, citations]
---

# PressGEO Local AI Visibility Benchmark

Weekly aggregate of how often AI search tools (ChatGPT, Perplexity, Google AI Overviews and others) name local service businesses when buyers ask for recommendations, across 20 U.S. metros and 13 service categories.

Last updated: 2026-10-29. Source and methodology: https://pressgeo.com/research

## Files
- `latest/metros.csv` / `latest/metros.json` — current metro-level snapshot
- `history/2026-10-29.csv` — dated weekly snapshots

## Columns
metro, city, state, firms_tracked, firms_checked, firms_cited, checks_90d, cited_share (share of checked firms named at least once; blank when no checks have run yet).

Only recorded checks are counted; firms not yet checked are never treated as cited or uncited.

License: CC BY 4.0 — please cite "PressGEO Local AI Visibility Benchmark" with a link to https://pressgeo.com/research.

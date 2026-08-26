# company-news-data (v2 archive)

Read-only, time-partitioned company-news archive. Served via
`raw.githubusercontent.com/yuacxshard1/company-news-data/main/`.

- `v2/config.json` — scheme versions + counts (start here)
- `v2/data/<Y>/<M>/<D>/<doc_id>.json` — one article per file (immutable)
- `v2/index/` — recent feed, per-company months, permalink buckets, taxonomy
- `v2/meta/timestamps.jsonl` — the only per-crawl-volatile file

Updated incrementally (new files + tiny index appends); do not treat as a CDN.

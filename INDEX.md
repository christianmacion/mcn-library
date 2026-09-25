# MCN Library — INDEX

> Always-updated live index of every entry in the MCN Library. MD
> primary (in-repo readable); HTML / PDF downloadable per entry.

**Library root:** `/` of this repo
**INDEX last regenerated:** 2026-07-10

---

## Categories

1. [Mentee Workbooks](#01-mentee-workbooks) — the "from the Ground Up" teaching series
2. ~~Craft Courses~~ — reserved, currently empty
5. ~~Reference Exemplars~~ — reserved, currently empty (third-party)
6. ~~Skill Definition~~ — reserved, currently empty (private infra)

---

## 01. Mentee Workbooks

| # | Workbook | Topics | Size |
|---|---------|--------|-----:|
| 1 | [Context Engineering — from the Ground Up](./01-Mentee-Workbooks/context-engineering/) | Context window discipline, retrieval primitives, M3 economy | README + HTML + PDF |
| 2 | [Obsidian Wikilinks and the Karpathy Wiki — from the Ground Up](./01-Mentee-Workbooks/obsidian-wikilinks/) | Hand-curated knowledge graphs, PPR-over-graph retrieval, **hooks pattern** | README + HTML + PDF (public edition) |
| 3 | [AI Architecture — from the Ground Up (Guide)](./01-Mentee-Workbooks/ai-architecture-guide/) | Multi-agent AI architecture, boundaries, orchestration | README + HTML + PDF |

---



## Refresh commands

```bash
# Clone this repo, then update the index
git pull origin main
python3 scripts/generate_index.py    # future: auto-gen this file
```

Or for a manual refresh, regenerate via the same `INDEX.md` by
walking every entry folder.

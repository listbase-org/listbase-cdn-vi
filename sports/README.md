# Thể thao (Sports)

3 datasets — 3,094 records

> Browse at [listbase.org/vi/sports/](https://listbase.org/vi/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [UEFA Champions League (Cúp C1 châu Âu) — toàn bộ trận đấu vòng chính 2011/12–2025/26 (1997)](vi-uefa-champions-league-tran-dau.json) | 1,997 | 1205 KB | [CSV](vi-uefa-champions-league-tran-dau_VI.csv) | [Excel](vi-uefa-champions-league-tran-dau_VI.xlsx) | [View](https://listbase.org/vi/sports/vi-uefa-champions-league-tran-dau/) |
| [Giải vô địch bóng đá thế giới (World Cup) — toàn bộ trận đấu vòng chung kết 1930–2026 (1068)](vi-world-cup-bong-da-tran-dau.json) | 1,068 | 588 KB | [CSV](vi-world-cup-bong-da-tran-dau_VI.csv) | [Excel](vi-world-cup-bong-da-tran-dau_VI.xlsx) | [View](https://listbase.org/vi/sports/vi-world-cup-bong-da-tran-dau/) |
| [Sân vận động ở Việt Nam](vi-san-van-dong.json) | 29 | 13 KB | [CSV](vi-san-van-dong_VI.csv) | [Excel](vi-san-van-dong_VI.xlsx) | [View](https://listbase.org/vi/sports/vi-san-van-dong/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/sports/vi-uefa-champions-league-tran-dau.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/sports/)

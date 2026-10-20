# Giáo dục (Education)

2 datasets — 94 records

> Browse at [listbase.org/vi/education/](https://listbase.org/vi/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Việt Nam — Các trường đại học](vi-truong-dai-hoc.json) | 58 | 19 KB | [CSV](vi-truong-dai-hoc_VI.csv) | [Excel](vi-truong-dai-hoc_VI.xlsx) | [View](https://listbase.org/vi/education/vi-truong-dai-hoc/) |
| [Trường học ở Việt Nam](vi-truong-hoc.json) | 36 | 16 KB | [CSV](vi-truong-hoc_VI.csv) | [Excel](vi-truong-hoc_VI.xlsx) | [View](https://listbase.org/vi/education/vi-truong-hoc/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/education/vi-truong-dai-hoc.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/education/)

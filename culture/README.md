# Văn hóa & Tôn giáo (Culture & Religion)

5 datasets — 210 records

> Browse at [listbase.org/vi/culture/](https://listbase.org/vi/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Bảo tàng tại Việt Nam (Museums in Vietnam)](vi-bao-tang.json) | 122 | 27 KB | [CSV](vi-bao-tang_VI.csv) | [Excel](vi-bao-tang_VI.xlsx) | [View](https://listbase.org/vi/culture/vi-bao-tang/) |
| [Vietnamese Buddhist Pagodas (Chùa) — Wikipedia](vi-chua-viet-nam.json) | 44 | 270 KB | [CSV](vi-chua-viet-nam_VI.csv) | [Excel](vi-chua-viet-nam_VI.xlsx) | [View](https://listbase.org/vi/culture/vi-chua-viet-nam/) |
| [Nhà thờ ở Việt Nam](vi-nha-tho.json) | 25 | 10 KB | [CSV](vi-nha-tho_VI.csv) | [Excel](vi-nha-tho_VI.xlsx) | [View](https://listbase.org/vi/culture/vi-nha-tho/) |
| [Rạp chiếu phim ở Việt Nam](vi-rap-chieu-phim.json) | 11 | 6 KB | [CSV](vi-rap-chieu-phim_VI.csv) | [Excel](vi-rap-chieu-phim_VI.xlsx) | [View](https://listbase.org/vi/culture/vi-rap-chieu-phim/) |
| [Di sản thế giới UNESCO tại Việt Nam](vi-di-san-the-gioi-unesco.json) | 8 | 10 KB | [CSV](vi-di-san-the-gioi-unesco_VI.csv) | [Excel](vi-di-san-the-gioi-unesco_VI.xlsx) | [View](https://listbase.org/vi/culture/vi-di-san-the-gioi-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/culture/vi-bao-tang.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/culture/)

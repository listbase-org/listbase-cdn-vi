# Lịch sử (History)

2 datasets — 174 records

> Browse at [listbase.org/vi/history/](https://listbase.org/vi/history/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Di tích quốc gia đặc biệt (Special National Heritage Sites of Vietnam)](vi-di-tich-quoc-gia-dac-biet.json) | 111 | 1074 KB | [CSV](vi-di-tich-quoc-gia-dac-biet_VI.csv) | [Excel](vi-di-tich-quoc-gia-dac-biet_VI.xlsx) | [View](https://listbase.org/vi/history/vi-di-tich-quoc-gia-dac-biet/) |
| [Việt Nam — 63 tỉnh thành (cấu trúc trước sáp nhập 2025)](vi-tinh-thanh-2019.json) | 63 | 11 KB | [CSV](vi-tinh-thanh-2019_VI.csv) | [Excel](vi-tinh-thanh-2019_VI.xlsx) | [View](https://listbase.org/vi/history/vi-tinh-thanh-2019/) |

## Quick Start

```bash
# List all history datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="history") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/history/vi-di-tich-quoc-gia-dac-biet.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/history/)

# Đơn vị đo lường (Units & Measurements)

4 datasets — 216 records

> Browse at [listbase.org/vi/units/](https://listbase.org/vi/units/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Bộ Dữ liệu Yếu tố Chuyển đổi Đơn vị Toàn diện](units-conversions.json) | 83 | 17 KB | [CSV](units-conversions_VI.csv) | [Excel](units-conversions_VI.xlsx) | [View](https://listbase.org/vi/units/units-conversions/) |
| [Temperature Conversion Matrix Dataset](units-temperatures.json) | 55 | 11 KB | [CSV](units-temperatures_VI.csv) | [Excel](units-temperatures_VI.xlsx) | [View](https://listbase.org/vi/units/units-temperatures/) |
| [Bộ Dữ Liệu Bảng Chuyển Đổi Kích Thước Giày Quốc Tế](units-shoe-sizes.json) | 43 | 8 KB | [CSV](units-shoe-sizes_VI.csv) | [Excel](units-shoe-sizes_VI.xlsx) | [View](https://listbase.org/vi/units/units-shoe-sizes/) |
| [Clothing Size Standards Dataset](units-clothing-sizes.json) | 35 | 10 KB | [CSV](units-clothing-sizes_VI.csv) | [Excel](units-clothing-sizes_VI.xlsx) | [View](https://listbase.org/vi/units/units-clothing-sizes/) |

## Quick Start

```bash
# List all units & measurements datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="units") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/units/units-conversions.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/units/)

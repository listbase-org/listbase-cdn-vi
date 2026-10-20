# Thực phẩm & Dinh dưỡng (Food & Nutrition)

2 datasets — 355 records

> Browse at [listbase.org/vi/food/](https://listbase.org/vi/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Nhà hàng Michelin tại Việt Nam](vi-nha-hang-michelin.json) | 193 | 195 KB | [CSV](vi-nha-hang-michelin_VI.csv) | [Excel](vi-nha-hang-michelin_VI.xlsx) | [View](https://listbase.org/vi/food/vi-nha-hang-michelin/) |
| [Bảng thành phần dinh dưỡng thực phẩm Việt Nam](vi-food-nutrition.json) | 162 | 79 KB | [CSV](vi-food-nutrition_VI.csv) | [Excel](vi-food-nutrition_VI.xlsx) | [View](https://listbase.org/vi/food/vi-food-nutrition/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/food/vi-nha-hang-michelin.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/food/)

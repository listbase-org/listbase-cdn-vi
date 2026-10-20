# Toán học (Mathematics)

3 datasets — 152 records

> Browse at [listbase.org/vi/math/](https://listbase.org/vi/math/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Bộ Dữ liệu Công thức Đạo hàm Phổ biến](math-derivative-formulas.json) | 57 | 13 KB | [CSV](math-derivative-formulas_VI.csv) | [Excel](math-derivative-formulas_VI.xlsx) | [View](https://listbase.org/vi/math/math-derivative-formulas/) |
| [Bộ dữ liệu Công thức Tích phân Thông dụng](math-integral-formulas.json) | 56 | 13 KB | [CSV](math-integral-formulas_VI.csv) | [Excel](math-integral-formulas_VI.xlsx) | [View](https://listbase.org/vi/math/math-integral-formulas/) |
| [Bộ dữ liệu bảng biến đổi Laplace toàn diện](math-laplace-transform.json) | 39 | 9 KB | [CSV](math-laplace-transform_VI.csv) | [Excel](math-laplace-transform_VI.xlsx) | [View](https://listbase.org/vi/math/math-laplace-transform/) |

## Quick Start

```bash
# List all mathematics datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="math") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/math/math-derivative-formulas.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/math/)

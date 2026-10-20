# Khoa học (Science)

9 datasets — 405 records

> Browse at [listbase.org/vi/science/](https://listbase.org/vi/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Bộ Dữ Liệu Bảng Tuần Hoàn Các Nguyên Tố Hóa Học Toàn Diện](science-periodic-table.json) | 118 | 39 KB | [CSV](science-periodic-table_VI.csv) | [Excel](science-periodic-table_VI.xlsx) | [View](https://listbase.org/vi/science/science-periodic-table/) |
| [Bộ Dữ liệu Bảng Codon RNA Hoàn chỉnh](science-codon-table.json) | 64 | 14 KB | [CSV](science-codon-table_VI.csv) | [Excel](science-codon-table_VI.xlsx) | [View](https://listbase.org/vi/science/science-codon-table/) |
| [Bộ Dữ Liệu Bảng Độ Âm Điện (Thang Pauling)](science-electronegativity.json) | 62 | 18 KB | [CSV](science-electronegativity_VI.csv) | [Excel](science-electronegativity_VI.xlsx) | [View](https://listbase.org/vi/science/science-electronegativity/) |
| [Tập dữ liệu Hệ thống Đơn vị Quốc tế (Đơn vị SI)](science-si-units.json) | 53 | 13 KB | [CSV](science-si-units_VI.csv) | [Excel](science-si-units_VI.xlsx) | [View](https://listbase.org/vi/science/science-si-units/) |
| [Tập dữ liệu Tham chiếu Thang pH và Tính chất Hóa học](science-ph-scale.json) | 33 | 9 KB | [CSV](science-ph-scale_VI.csv) | [Excel](science-ph-scale_VI.xlsx) | [View](https://listbase.org/vi/science/science-ph-scale/) |
| [Bộ Dữ Liệu Bảng Quy Tắc Độ Tan Toàn Diện](science-solubility-rules.json) | 31 | 12 KB | [CSV](science-solubility-rules_VI.csv) | [Excel](science-solubility-rules_VI.xlsx) | [View](https://listbase.org/vi/science/science-solubility-rules/) |
| [Bộ dữ liệu thuộc tính Axit Amin toàn diện](science-amino-acids.json) | 22 | 11 KB | [CSV](science-amino-acids_VI.csv) | [Excel](science-amino-acids_VI.xlsx) | [View](https://listbase.org/vi/science/science-amino-acids/) |
| [Bộ Dữ Liệu Biểu Đồ Tương Thích Nhóm Máu Toàn Diện](science-blood-types.json) | 11 | 7 KB | [CSV](science-blood-types_VI.csv) | [Excel](science-blood-types_VI.xlsx) | [View](https://listbase.org/vi/science/science-blood-types/) |
| [Bộ Dữ liệu Hành tinh & Thiên thể Hệ Mặt trời](science-planet-data.json) | 11 | 11 KB | [CSV](science-planet-data_VI.csv) | [Excel](science-planet-data_VI.xlsx) | [View](https://listbase.org/vi/science/science-planet-data/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/science/science-periodic-table.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/science/)

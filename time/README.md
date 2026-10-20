# Thời gian & Lịch (Time & Calendar)

6 datasets — 11,036 records

> Browse at [listbase.org/vi/time/](https://listbase.org/vi/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Bảng chuyển đổi Dương lịch ↔ Âm lịch Việt Nam (1950–2099)](vi-am-lich-conversions.json) | 5,000 | 1263 KB | [CSV](vi-am-lich-conversions_VI.csv) | [Excel](vi-am-lich-conversions_VI.xlsx) | [View](https://listbase.org/vi/time/vi-am-lich-conversions/) |
| [Lịch âm dương Việt Nam — cặp ngày dương–âm (1950–2099)](vi-lich-am-duong.json) | 4,792 | 1450 KB | [CSV](vi-lich-am-duong_VI.csv) | [Excel](vi-lich-am-duong_VI.xlsx) | [View](https://listbase.org/vi/time/vi-lich-am-duong/) |
| [Ngày lễ và Tết Việt Nam (1901–2030) — multilingual completos](vi-ngay-le-completos.json) | 1,193 | 413 KB | [CSV](vi-ngay-le-completos_VI.csv) | [Excel](vi-ngay-le-completos_VI.xlsx) | [View](https://listbase.org/vi/time/vi-ngay-le-completos/) |
| [Ngày lễ và ngày kỷ niệm ở Việt Nam](vi-ngay-le.json) | 27 | 11 KB | [CSV](vi-ngay-le_VI.csv) | [Excel](vi-ngay-le_VI.xlsx) | [View](https://listbase.org/vi/time/vi-ngay-le/) |
| [Bộ Dữ liệu 12 Con Giáp Trung Quốc Toàn Diện](time-chinese-zodiac.json) | 12 | 12 KB | [CSV](time-chinese-zodiac_VI.csv) | [Excel](time-chinese-zodiac_VI.xlsx) | [View](https://listbase.org/vi/time/time-chinese-zodiac/) |
| [Dữ liệu Cung Hoàng Đạo Phương Tây Toàn Diện](time-zodiac-signs.json) | 12 | 10 KB | [CSV](time-zodiac-signs_VI.csv) | [Excel](time-zodiac-signs_VI.xlsx) | [View](https://listbase.org/vi/time/time-zodiac-signs/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/time/vi-am-lich-conversions.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/time/)

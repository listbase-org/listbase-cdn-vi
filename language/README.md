# Ngôn ngữ (Language)

6 datasets — 1,184 records

> Browse at [listbase.org/vi/language/](https://listbase.org/vi/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Ngôn ngữ thế giới](vi-ngon-ngu-the-gioi.json) | 591 | 55 KB | [CSV](vi-ngon-ngu-the-gioi_VI.csv) | [Excel](vi-ngon-ngu-the-gioi_VI.xlsx) | [View](https://listbase.org/vi/language/vi-ngon-ngu-the-gioi/) |
| [Bảng Âm Tiết Pinyin Tiếng Trung Toàn Diện & Hướng Dẫn Phát Âm](lang-pinyin-table.json) | 408 | 101 KB | [CSV](lang-pinyin-table_VI.csv) | [Excel](lang-pinyin-table_VI.xlsx) | [View](https://listbase.org/vi/language/lang-pinyin-table/) |
| [Bộ Dữ Liệu Bảng Phân Loại Đại Từ Tiếng Anh](lang-english-pronouns.json) | 69 | 22 KB | [CSV](lang-english-pronouns_VI.csv) | [Excel](lang-english-pronouns_VI.xlsx) | [View](https://listbase.org/vi/language/lang-english-pronouns/) |
| [Bộ Dữ liệu Bảng Hiragana Nhật Bản & Ánh xạ Romaji](lang-hiragana-table.json) | 46 | 11 KB | [CSV](lang-hiragana-table_VI.csv) | [Excel](lang-hiragana-table_VI.xlsx) | [View](https://listbase.org/vi/language/lang-hiragana-table/) |
| [Bộ Dữ Liệu Bảng Ký Tự Katakana Tiếng Nhật Hoàn Chỉnh](lang-katakana-table.json) | 46 | 11 KB | [CSV](lang-katakana-table_VI.csv) | [Excel](lang-katakana-table_VI.xlsx) | [View](https://listbase.org/vi/language/lang-katakana-table/) |
| [Bộ Dữ Liệu Các Ký Tự Bảng Chữ Cái Hy Lạp Hoàn Chỉnh](lang-greek-alphabet.json) | 24 | 10 KB | [CSV](lang-greek-alphabet_VI.csv) | [Excel](lang-greek-alphabet_VI.xlsx) | [View](https://listbase.org/vi/language/lang-greek-alphabet/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/language/vi-ngon-ngu-the-gioi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/language/)

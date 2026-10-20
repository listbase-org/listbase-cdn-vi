# Công nghệ (Technology)

13 datasets — 925 records

> Browse at [listbase.org/vi/tech/](https://listbase.org/vi/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Bộ Dữ Liệu Mã Ngôn Ngữ ISO 639 & Tên Bản Địa](tech-language-codes.json) | 183 | 26 KB | [CSV](tech-language-codes_VI.csv) | [Excel](tech-language-codes_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-language-codes/) |
| [Bộ Dữ Liệu Bảng & Mã Tham Chiếu Ký Tự ASCII Hoàn Chỉnh](tech-ascii-table.json) | 128 | 28 KB | [CSV](tech-ascii-table_VI.csv) | [Excel](tech-ascii-table_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-ascii-table/) |
| [Tập Dữ Liệu Phím Tắt Phổ Biến cho Windows và macOS](tech-keyboard-shortcuts.json) | 77 | 17 KB | [CSV](tech-keyboard-shortcuts_VI.csv) | [Excel](tech-keyboard-shortcuts_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-keyboard-shortcuts/) |
| [Bộ dữ liệu Thực thể Ký tự HTML & Biểu tượng Đặc biệt](tech-html-entities.json) | 75 | 18 KB | [CSV](tech-html-entities_VI.csv) | [Excel](tech-html-entities_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-html-entities/) |
| [Tập dữ liệu số cổng mạng và dịch vụ phổ biến](tech-port-numbers.json) | 73 | 16 KB | [CSV](tech-port-numbers_VI.csv) | [Excel](tech-port-numbers_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-port-numbers/) |
| [Tập dữ liệu các loại MIME và phần mở rộng tệp phổ biến](tech-mime-types.json) | 70 | 14 KB | [CSV](tech-mime-types_VI.csv) | [Excel](tech-mime-types_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-mime-types/) |
| [Bộ Dữ Liệu Biểu Tượng Unicode & Thực Thể HTML Phổ Biến](tech-unicode-symbols.json) | 70 | 15 KB | [CSV](tech-unicode-symbols_VI.csv) | [Excel](tech-unicode-symbols_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-unicode-symbols/) |
| [HTTP Status Codes Dataset](tech-http-codes.json) | 62 | 16 KB | [CSV](tech-http-codes_VI.csv) | [Excel](tech-http-codes_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-http-codes/) |
| [Bộ Dữ Liệu Các Mẫu Biểu Thức Chính Quy Thiết Yếu](tech-regex-patterns.json) | 45 | 13 KB | [CSV](tech-regex-patterns_VI.csv) | [Excel](tech-regex-patterns_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-regex-patterns/) |
| [Bộ Dữ Liệu Kích Thước & Định Dạng Ảnh Mạng Xã Hội](tech-social-media-sizes.json) | 42 | 13 KB | [CSV](tech-social-media-sizes_VI.csv) | [Excel](tech-social-media-sizes_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-social-media-sizes/) |
| [Screen Resolutions & Aspect Ratios Dataset](tech-screen-resolutions.json) | 35 | 10 KB | [CSV](tech-screen-resolutions_VI.csv) | [Excel](tech-screen-resolutions_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-screen-resolutions/) |
| [Bộ Dữ Liệu Kích Thước Giấy & Kích Thước Pixel](tech-paper-sizes.json) | 33 | 13 KB | [CSV](tech-paper-sizes_VI.csv) | [Excel](tech-paper-sizes_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-paper-sizes/) |
| [Bộ Dữ Liệu Bảng Chân Lý Cổng Logic](tech-logic-gates.json) | 32 | 10 KB | [CSV](tech-logic-gates_VI.csv) | [Excel](tech-logic-gates_VI.xlsx) | [View](https://listbase.org/vi/tech/tech-logic-gates/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/tech/tech-language-codes.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/tech/)

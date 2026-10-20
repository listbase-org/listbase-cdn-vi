# Tài chính & Thương mại (Finance & Trade)

14 datasets — 7,488 records

> Browse at [listbase.org/vi/finance/](https://listbase.org/vi/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Mã chứng khoán Việt Nam — theo sàn niêm yết](vi-chung-khoan-ma-niem-yet.json) | 2,758 | 552 KB | [CSV](vi-chung-khoan-ma-niem-yet_VI.csv) | [Excel](vi-chung-khoan-ma-niem-yet_VI.xlsx) | [View](https://listbase.org/vi/finance/vi-chung-khoan-ma-niem-yet/) |
| [Công ty niêm yết Việt Nam — phân loại theo ngành ICB](vi-cong-ty-niem-yet-theo-nganh.json) | 1,592 | 604 KB | [CSV](vi-cong-ty-niem-yet-theo-nganh_VI.csv) | [Excel](vi-cong-ty-niem-yet-theo-nganh_VI.xlsx) | [View](https://listbase.org/vi/finance/vi-cong-ty-niem-yet-theo-nganh/) |
| [Mã chứng khoán đã hủy niêm yết](vi-chung-khoan-da-huy-niem-yet.json) | 914 | 176 KB | [CSV](vi-chung-khoan-da-huy-niem-yet_VI.csv) | [Excel](vi-chung-khoan-da-huy-niem-yet_VI.xlsx) | [View](https://listbase.org/vi/finance/vi-chung-khoan-da-huy-niem-yet/) |
| [Mã chứng khoán — Sàn UPCOM](vi-chung-khoan-upcom.json) | 887 | 187 KB | [CSV](vi-chung-khoan-upcom_VI.csv) | [Excel](vi-chung-khoan-upcom_VI.xlsx) | [View](https://listbase.org/vi/finance/vi-chung-khoan-upcom/) |
| [Mã chứng khoán — Sàn HSX (HOSE)](vi-chung-khoan-hsx.json) | 568 | 113 KB | [CSV](vi-chung-khoan-hsx_VI.csv) | [Excel](vi-chung-khoan-hsx_VI.xlsx) | [View](https://listbase.org/vi/finance/vi-chung-khoan-hsx/) |
| [Mã chứng khoán — Sàn HNX](vi-chung-khoan-hnx.json) | 321 | 67 KB | [CSV](vi-chung-khoan-hnx_VI.csv) | [Excel](vi-chung-khoan-hnx_VI.xlsx) | [View](https://listbase.org/vi/finance/vi-chung-khoan-hnx/) |
| [Bộ Dữ liệu Mã Tiền tố & Quốc gia GS1 (Mã Vạch)](finance-gs1-codes.json) | 126 | 20 KB | [CSV](finance-gs1-codes_VI.csv) | [Excel](finance-gs1-codes_VI.xlsx) | [View](https://listbase.org/vi/finance/finance-gs1-codes/) |
| [Tập dữ liệu Chương Mã HS (Hệ thống hài hòa)](finance-hs-codes.json) | 98 | 24 KB | [CSV](finance-hs-codes_VI.csv) | [Excel](finance-hs-codes_VI.xlsx) | [View](https://listbase.org/vi/finance/finance-hs-codes/) |
| [Bộ Dữ liệu Thuế Suất VAT/GST Toàn Diện theo Quốc gia](finance-vat-rates.json) | 75 | 18 KB | [CSV](finance-vat-rates_VI.csv) | [Excel](finance-vat-rates_VI.xlsx) | [View](https://listbase.org/vi/finance/finance-vat-rates/) |
| [Trái phiếu Việt Nam — danh sách](vi-trai-phieu.json) | 68 | 14 KB | [CSV](vi-trai-phieu_VI.csv) | [Excel](vi-trai-phieu_VI.xlsx) | [View](https://listbase.org/vi/finance/vi-trai-phieu/) |
| [Chỉ số VN30 — Cổ phiếu thành phần](vi-vn30-co-phieu.json) | 30 | 7 KB | [CSV](vi-vn30-co-phieu_VI.csv) | [Excel](vi-vn30-co-phieu_VI.xlsx) | [View](https://listbase.org/vi/finance/vi-vn30-co-phieu/) |
| [Chợ ở Việt Nam](vi-cho.json) | 26 | 10 KB | [CSV](vi-cho_VI.csv) | [Excel](vi-cho_VI.xlsx) | [View](https://listbase.org/vi/finance/vi-cho/) |
| [Bộ dữ liệu mã và thông số kỹ thuật container ISO 6346](finance-container-codes.json) | 14 | 8 KB | [CSV](finance-container-codes_VI.csv) | [Excel](finance-container-codes_VI.xlsx) | [View](https://listbase.org/vi/finance/finance-container-codes/) |
| [Bộ dữ liệu Quy tắc & Định nghĩa Incoterms 2020](finance-incoterms.json) | 11 | 9 KB | [CSV](finance-incoterms_VI.csv) | [Excel](finance-incoterms_VI.xlsx) | [View](https://listbase.org/vi/finance/finance-incoterms/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/finance/vi-chung-khoan-ma-niem-yet.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/finance/)

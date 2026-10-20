# ListBase CDN — Tiếng Việt (vi)

Open dataset collection for **Tiếng Việt** (Vietnamese).
477 datasets across 17 categories with 115,834 total records.

> Browse and download at [https://listbase.org/vi/](https://listbase.org/vi/)

## Categories

| Category | Datasets |
|----------|----------|
| [Văn hóa & Tôn giáo (Culture & Religion)](culture/) | 5 |
| [Giáo dục (Education)](education/) | 2 |
| [Tài chính & Thương mại (Finance & Trade)](finance/) | 14 |
| [Thực phẩm & Dinh dưỡng (Food & Nutrition)](food/) | 2 |
| [Địa lý (Geography)](geography/) | 40 |
| [Lịch sử (History)](history/) | 2 |
| [Ngôn ngữ (Language)](language/) | 6 |
| [Toán học (Mathematics)](math/) | 3 |
| [Âm nhạc (Music)](music/) | 2 |
| [Tham khảo (Reference)](reference/) | 276 |
| [Khoa học (Science)](science/) | 9 |
| [Thể thao (Sports)](sports/) | 3 |
| [Công nghệ (Technology)](tech/) | 13 |
| [Thời gian & Lịch (Time & Calendar)](time/) | 6 |
| [Du lịch (Tourism)](tourism/) | 64 |
| [Giao thông (Transport)](transport/) | 26 |
| [Đơn vị đo lường (Units & Measurements)](units/) | 4 |

## Usage

### Browse on the web
Visit [listbase.org/vi/](https://listbase.org/vi/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.vi.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.vi.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.vi.listbase.org/geography/th-central-provinces_VI.xlsx
curl -O https://cdn.vi.listbase.org/geography/th-central-provinces_VI.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.vi.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.vi.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_VI.csv   # CSV download
│   └── {dataset}_VI.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists

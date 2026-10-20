# Âm nhạc (Music)

2 datasets — 162 records

> Browse at [listbase.org/vi/music/](https://listbase.org/vi/music/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Tập Dữ Liệu Tham Chiếu Biểu Đồ Hợp Âm Piano Thiết Yếu](music-piano-chords.json) | 84 | 22 KB | [CSV](music-piano-chords_VI.csv) | [Excel](music-piano-chords_VI.xlsx) | [View](https://listbase.org/vi/music/music-piano-chords/) |
| [Bộ Dữ Liệu Biểu Đồ Hợp Âm Guitar Toàn Diện](music-guitar-chords.json) | 78 | 24 KB | [CSV](music-guitar-chords_VI.csv) | [Excel](music-guitar-chords_VI.xlsx) | [View](https://listbase.org/vi/music/music-guitar-chords/) |

## Quick Start

```bash
# List all music datasets
curl https://cdn.vi.listbase.org/index.json | jq '.datasets[] | select(.category=="music") | .id'

# Fetch a dataset
curl https://cdn.vi.listbase.org/music/music-piano-chords.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/vi/music/)

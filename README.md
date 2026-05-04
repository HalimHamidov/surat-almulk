# 🌙 Surat Al-Mulk — Memorization Website(s)

Comparing AI-generated memorization tools for Surah Al-Mulk (Quran 67).

## Live Sites

| Version | URL |
|---|---|
| 🏠 Landing | `https://halimhamidov.github.io/surat-almulk/` |
| 🤖 Claude | `https://halimhamidov.github.io/surat-almulk/claude/` |
| ✨ Manus | `https://halimhamidov.github.io/surat-almulk/manus/` |

## Repo Structure

```
surat-almulk/
├── index.html        ← Landing page (choose version)
├── README.md
├── claude/
│   ├── index.html    ← Claude (Anthropic) version
│   └── README.md
└── manus/
    ├── index.html    ← Manus version (add when ready)
    └── README.md
```

## GitHub Pages Setup

1. Go to **Settings → Pages**
2. Source: `Deploy from a branch` → branch `main`, folder `/ (root)`
3. Save — GitHub will serve all subfolders automatically

## Adding the Manus Version

Simply drop Manus's `index.html` into the `manus/` folder and push:

```bash
cp /path/to/manus-output.html manus/index.html
git add manus/
git commit -m "Add Manus version"
git push
```

## Sources

- Arabic text: [Quran.com/67](https://quran.com/67)
- Russian translations: [umma.ru](https://umma.ru)
- Hadith reference: [Tirmidhi 2890](https://sunnah.com/tirmidhi:2890)

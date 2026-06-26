# Aile2017.github.io

This is Aile2017's GitHub Pages portfolio site.

- URL: https://aile2017.github.io/
- Content: About / Projects / Contact on a single page

## Projects

### GreenPad
- Repository: https://github.com/Aile2017/GreenPad
- Overview: A lightweight text editor for Windows x64.

### GreenPad-translations
- Repository: https://github.com/Aile2017/GreenPad-translations
- Overview:
  A translation repository that manages GreenPad language files (.lng).
  In addition to the 6 upstream languages (English, Japanese, Chinese Simplified/Traditional,
  Korean, and Russian), it also maintains additional languages such as French and German.
- Synchronization:
  GitHub Actions performs daily sync from upstream, and newly added keys are automatically
  inserted with a `[TODO]` marker.

### GreenPad-keywords
- Repository: https://github.com/Aile2017/GreenPad-keywords
- Overview:
  A repository that manages GreenPad syntax-highlighting keyword files (.kwd).
  It provides keyword definitions for multiple languages and file formats, including
  both major and niche languages.
- Format:
  Each `.kwd` file defines syntax-highlighting behavior such as case sensitivity,
  comment delimiters, quoted strings, and escape-sequence handling.

### Aile
- Repository: https://github.com/Aile2017/Aile
- Overview:
  A unified Windows archive manager GUI that seamlessly integrates the robust multi-format support of 7z.dll with the flexibility of script-based execution (B2E).
- Features:
  Browse archive contents with tree and list view, extract archives, create archives with format and compression method selection. Multi-format support (7z / ZIP / TAR / GZip / BZip2 / XZ / Zstd and more), encrypted archive support with password prompt, split-volume handling, and a bilingual UI (English/Japanese). Features recent archives history and drag & drop support, fully DPI-aware (Per-Monitor V2).

### libchardet
- Repository: https://github.com/Aile2017/libchardet
- Overview: A C/C++ library used by GreenPad for automatic character encoding detection.

### pcre2
- Repository: https://github.com/Aile2017/pcre2
- Overview: A C library used by GreenPad for regular expression search functionality.

## Repository Structure

```text
.
|- Aile2017.png
|- google6ea1fa549685cbc2.html
|- index.html
|- README.md
|- robots.txt
|- sitemap.xml
|- css/
|  `- style.css
```

## Local Preview

Since this is a static site, you can preview it by opening `index.html` in your browser.
If needed, use a local server such as Live Server.

# 🐙 Octopus Reader — Book Search & Reading App

<p align="center">
  <img src="https://raw.githubusercontent.com/twitter/twemoji/master/assets/svg/1f4da.svg" alt="Octopus Reader" width="120"/>
</p>

<p align="center">
  <b>A reader with full-library search and citation collection system</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue?style=flat-square&logo=windows"/>
  <img src="https://img.shields.io/badge/Android-coming%20soon-green?style=flat-square&logo=android"/>
  <img src="https://img.shields.io/badge/Python-3.10+-yellow?style=flat-square&logo=python"/>
  <img src="https://img.shields.io/badge/License-MIT-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Made%20by-NeuroOctopus-purple?style=flat-square"/>
</p>

---

## ✨ What the App Can Do

### 🔍 Search Across Your Entire Library
Load a whole book series at once and search for any word or phrase
across **all books simultaneously** — no need to open each book
one by one anymore.

> Search uses smart pattern matching — finds the word and all its forms.
> Example: searching `love` will also find `loved`, `lovely`, `lover`.

### 📌 Citation Collections
Found a passage you love? Add it to a collection with a single click.
Create as many collections as you want — by theme, character, or idea.

- ✅ The app will warn you if a quote is already saved — **no duplicates, ever**
- ✅ Rename and delete collections at any time
- ✅ All collections are **saved automatically** between sessions

### 📖 Fragment Expansion
Found the right paragraph but need more context?
Expand the fragment using **"Paragraph Up"** and **"Paragraph Down"** buttons —
then save it to your collection complete with context.
◀ Paragraph above   |   Remove above   |   Remove below   |   Paragraph below ▶


### 📤 Export Your Collections
Export any finished collection of quotes to:

| Format | |
|--------|-|
| 📄 TXT | plain text |
| 📝 DOCX | Word document |
| 📕 PDF | ready to print |

### 🌍 Two Languages
Switch between **Russian** and **English** interface at any time —
right in the top bar. The choice is saved automatically.

### 💾 Auto-Save Session
Every time you close the app — your books, collections and language
are saved. Open the app again and everything is right where you left it.

---

## 📂 Supported Formats

| Format | Description |
|--------|-------------|
| `.txt` | Plain text |
| `.epub` | E-books |
| `.fb2` | FictionBook |
| `.pdf` | PDF documents |
| `.docx` | Microsoft Word |
| `.djvu` | DjVu *(requires DjVuLibre)* |
| `.azw` `.azw3` | Amazon Kindle *(requires Calibre)* |
| `.mobi` | Mobipocket *(requires Calibre)* |
| `.lrf` | Sony Reader *(requires Calibre)* |

> 💡 For `.djvu` install [DjVuLibre](http://djvu.sourceforge.net/)
> For `.azw`, `.mobi`, `.lrf` install [Calibre](https://calibre-ebook.com/)

---

## 🖥️ Screenshots

> *(coming soon — if you'd like to help, send a screenshot in your review!)*

---

## 🚀 Installation & Launch

### Option 1 — Ready-to-use .exe (Windows)
1. Download the latest release from the [Releases](../../releases) page
2. Run `octopus_reader.exe`
3. No installation required ✅

### Option 2 — From Source Code

```bash
# 1. Clone the repository
git clone https://github.com/Elzje/octopus_reader.git
cd octopus_reader

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run
python reader.py
```
### Requirements

| | |
|-|-|
| 🐍 | Python 3.10+ |
| 🖥️ | Windows 10/11 |

---

## 📦 Dependencies

| Library | Purpose |
|---------|---------|
| `PyQt6` | Interface |
| `EbookLib` | EPUB support |
| `beautifulsoup4` | HTML parsing (epub, fb2) |
| `lxml` | XML parsing (fb2) |
| `pymupdf` | PDF support |
| `python-docx` | DOCX support |
| `reportlab` | PDF export |
| `loguru` | Logging |
| `pillow` | Image support |

---

## 🗺️ Roadmap

| Status | Feature |
|--------|---------|
| ✅ | Windows version |
| ✅ | Search across multiple books simultaneously |
| ✅ | Collections and export (TXT / DOCX / PDF) |
| ✅ | Russian and English interface |
| ✅ | Auto-save session |
| 🔄 | Android version *(Android Studio is already open!)* |
| 📋 | Cloud sync for collections |
| 📋 | Dark theme |
| 📋 | Search history |
| 📋 | Font and color customization |

---

## 🤝 Dependencies Roadmap

| Library | Purpose | Status |
|---------|---------|--------|
| `PyQt6` | UI framework | ✅ stable |
| `PyMuPDF` | PDF reading | ✅ stable |
| `EbookLib` | EPUB reading | ✅ stable |
| `ReportLab` | PDF export | ✅ stable |
| `Android SDK` | Mobile version | 🔄 in progress |

---

## 💬 About Us

<p align="center">
  Made with 🐙 by <b>NeuroOctopus</b> studio
</p>

<p align="center">
  <a href="https://t.me/neuroctopus">📱 t.me/neuroctopus</a>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <a href="../../issues">🐛 GitHub Issues</a>
</p>

---

## 📣 Feedback & Testing

Found a bug or have an idea?

| Step | Action |
|------|--------|
| 1 | Open [Issues](../../issues) |
| 2 | Click **New Issue** |
| 3 | Describe what happened |

> We read everything! 🐙

---

## 📄 License

This project is licensed under the **MIT License** —
feel free to use, modify and share.

See [LICENSE](LICENSE) for details.

<div align="center">

# Hi, I'm Roman 👋

**Senior Backend Developer · Go & Python · distributed systems**

10+ years in backend: demand planning & supply chain, BI platforms, iGaming, fintech.<br>
In open source I build tools that are safe to run on real data — read-only by default, dry-run first,<br>
verified against reference implementations.

[![Habr](https://img.shields.io/badge/Habr-articles-65A3BE?logo=habr&logoColor=white)](https://habr.com/ru/users/formeo/)
[![audiotools.dev](https://img.shields.io/badge/audiotools.dev-website-111?logo=googlechrome&logoColor=white)](https://audiotools.dev)
[![Boosty](https://img.shields.io/badge/Boosty-support-F15F2C?logo=boosty&logoColor=white)](https://boosty.to/formeo)

</div>

---

## ⭐ Featured — [fbrescue](https://github.com/formeo/fbrescue)

> **Recover data from a corrupted Firebird database when `gbak` gives up.**

[![Release](https://img.shields.io/github/v/release/formeo/fbrescue?label=release)](https://github.com/formeo/fbrescue/releases)
[![Stars](https://img.shields.io/github/stars/formeo/fbrescue?style=flat)](https://github.com/formeo/fbrescue/stargazers)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Firebird](https://img.shields.io/badge/Firebird-2.5--5.0-F40F02)
![License](https://img.shields.io/badge/license-MIT-green)

- 🔒 **Never modifies your file** — opens it read-only, checked by a test in CI
- 📦 **One binary** for Windows, Linux and macOS — no Firebird engine, no `fbclient`, no cgo
- 🩹 Reads damaged files: lost pointer pages, misplaced pages, broken TIP and header, tables missing from system catalogs
- 📤 Exports to **CSV, SQL, JSONL** — row versions, BLOBs, Firebird 4 types
- 🧪 Recovery measured on an open corpus: **13 kinds of damage, 520 damaged database copies**

[**Website & guides**](https://formeo.github.io/fbrescue/) · [Releases](https://github.com/formeo/fbrescue/releases) · [Repository](https://github.com/formeo/fbrescue)

---

## 🔊 Audio tools — [audiotools.dev](https://audiotools.dev)

Free browser tools (convert, trim, join, boost volume, change speed, compress, text-to-speech, voice-to-text) plus open-source CLI tools for the heavy lifting.

| Project | What it does | |
|---|---|---|
| 🎵 [**music_recognition**](https://github.com/formeo/music_recognition) | Identify and tag a whole music folder via Shazam — strong on electronic music, promos and edits where AcoustID misses | [![Stars](https://img.shields.io/github/stars/formeo/music_recognition?style=flat&label=★)](https://github.com/formeo/music_recognition) [![PyPI](https://img.shields.io/pypi/v/music-recognition-tool?label=PyPI)](https://pypi.org/project/music-recognition-tool/) |
| 📚 [**Audiobook-Cleaner**](https://github.com/formeo/Audiobook-Cleaner) | Remove background music and noise from multi-hour audiobooks (MDX-Net / Roformer), chunked and resumable | [![Stars](https://img.shields.io/github/stars/formeo/Audiobook-Cleaner?style=flat&label=★)](https://github.com/formeo/Audiobook-Cleaner) |
| 🎙 [**voice-to-text**](https://github.com/formeo/voice-to-text) | Bulk transcription of Telegram / WhatsApp voice messages with Whisper — CLI and Python API | [![Stars](https://img.shields.io/github/stars/formeo/voice-to-text?style=flat&label=★)](https://github.com/formeo/voice-to-text) |
| 🌐 [**audiotools.dev**](https://github.com/formeo/audiotools.dev) | Source of the website | [![Website](https://img.shields.io/badge/open-site-111)](https://audiotools.dev) |

---

## 🔬 Science

| Project | What it does | |
|---|---|---|
| ⚛️ [**amrl-transport**](https://github.com/formeo/amrl-transport) | Hardware-agnostic interface for autonomous atom manipulation with STM: simulator, RL-ready, distributed task queue | [![PyPI](https://img.shields.io/pypi/v/amrl-transport?label=PyPI)](https://pypi.org/project/amrl-transport/) |
| 🌀 [chi-space-theory](https://github.com/formeo/chi-space-theory) · [psi-field](https://github.com/formeo/psi-field) | Hobby: quantum-foundations thought experiments with Python simulations | ![Experimental](https://img.shields.io/badge/status-experimental-lightgrey) |

**Contributions:**
[heatrapy](https://github.com/djsilva99/heatrapy/pull/73) — vectorized 1D heat-transfer solvers ·
[SeQUeNCe](https://github.com/sequence-toolbox/SeQUeNCe/pull/328) — Python 3.11 deprecation & typing ·
[statsforecast](https://github.com/Nixtla/statsforecast) — UCM model

---

## 🗄 Firebird

| Project | What it does |
|---|---|
| [**fbrescue**](https://github.com/formeo/fbrescue) | ⭐ Read-only data recovery for Firebird 2.5–5.0 (see above) |
| [gobak](https://github.com/pharmacy72/gobak) | `nbackup` utility for Firebird, in Go |
| [FirebirdRepairBase](https://github.com/formeo/FirebirdRepairBase) | Earlier Delphi page analyzer — **superseded by fbrescue** |

---

## 🧰 Stack

![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Firebird](https://img.shields.io/badge/Firebird-F40F02?logo=firebird&logoColor=white)
![Delphi](https://img.shields.io/badge/Delphi-EE1F35?logo=delphi&logoColor=white)

<sub>Other experiments: [go-audio-converter](https://github.com/formeo/go-audio-converter) — pure-Go audio converter without FFmpeg (experimental).</sub>

# 🦉 OConvertX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OUtils%20%2F%20Data%20Conversion-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Interface-GUI%20%28Tkinter%29-blueviolet?style=flat-square"/>
  <img src="https://img.shields.io/badge/No%20Dependencies-Stdlib%20Only-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **OConvertX** is a dark-themed GUI data encoder and decoder suite — 20 conversion methods across text, binary, numeric, cipher, and Morse formats, with live input stats, swap input/output chaining, session history, and JSON/TXT export.

---

## 📌 Overview

OConvertX provides a clean Tkinter interface (1200×800) for rapid data encoding and decoding. A dropdown selector and quick-group buttons give instant access to any conversion. The output of one operation can be fed directly into the next via the **Use as Input** button — enabling multi-step encoding chains without leaving the window.

---

## 🖥️ Interface Tabs

| Tab | Contents |
|-----|---------|
| **CONVERTER** | Input textarea · Convert button · Output textarea with Copy and Use-as-Input actions |
| **HISTORY** | Treeview of all session conversions — timestamp, method, input/output previews; click for full detail |
| **REFERENCE** | Built-in quick examples for every conversion group with sample inputs and outputs |
| **ABOUT** | Tool info and total conversion count |

---

## 🔄 Conversion Methods — 20 Total

### TEXT ↔ HEX
| Method | Example |
|--------|---------|
| Text → Hex | `Hello` → `48656c6c6f` |
| Hex → Text | `48656c6c6f` → `Hello` |

### TEXT ↔ BINARY
| Method | Example |
|--------|---------|
| Text → Binary | `Hi` → `01001000 01101001` |
| Binary → Text | `01001000` → `H` |

### TEXT ↔ ASCII DECIMAL
| Method | Example |
|--------|---------|
| Text → ASCII Decimal | `ABC` → `65, 66, 67` |
| ASCII Decimal → Text | `65, 66, 67` → `ABC` |

### TEXT ↔ BASE64
| Method | Example |
|--------|---------|
| Text → Base64 | `owlsec` → `b3dsc2Vj` |
| Base64 → Text | `b3dsc2Vj` → `owlsec` |

### TEXT ↔ URL
| Method | Example |
|--------|---------|
| Text → URL Encode | `hello world!` → `hello%20world%21` |
| URL → Text | `hello%20world` → `hello world` |

### CIPHER
| Method | Note |
|--------|------|
| ROT13 | Symmetric — apply twice to restore original |

### TEXT ↔ MORSE
| Method | Example |
|--------|---------|
| Text → Morse | `SOS` → `... --- ...` |
| Morse → Text | `... --- ...` → `SOS` |

### NUM CONVERT (numeric values)
| Method | Example |
|--------|---------|
| Hex → Binary (number) | `FF` → `11111111` |
| Binary → Hex (number) | `1111` → `F` |
| Dec → Hex (number) | `255` → `FF` |
| Hex → Dec (number) | `FF` → `255` |

### TRANSFORM
| Method | Description |
|--------|-------------|
| Reverse String | Flip entire input backwards |
| Toggle Case | Swap upper/lower case for each character |

### ANALYSE
| Method | Output |
|--------|--------|
| String Statistics | Character count · word count · line count · unique characters · UTF-8 byte size |

---

## 🎛️ Sidebar Controls

| Section | Controls |
|---------|---------|
| **CONVERSION TYPE** | Dropdown with all 20 methods |
| **QUICK GROUPS** | One-click jump to first method of each group: HEX · BINARY · ASCII · BASE64 · URL · CIPHER · MORSE · NUM · TRANSFORM · ANALYSE |
| **ACTIONS** | Convert · Swap Input↔Output · Clear All |
| **CLIPBOARD** | Paste to Input · Copy Output |
| **LIVE STATS** | Input chars · Input bytes (UTF-8) · Input words · Output chars — updated on every keystroke |
| **EXPORT HISTORY** | Export JSON · Export TXT · Clear History |

---

## 📤 Export

Session history exported via native file-save dialog:

| Format | Contents |
|--------|----------|
| **JSON** | Tool metadata, export timestamp, list of all conversions: timestamp, method, full input, full output |
| **TXT** | Human-readable log of all conversions |

---

## ⚙️ Requirements

- **Linux or Windows** with a display
- **No Python installation needed** — runs as a standalone executable
- **No external dependencies** — Tkinter and stdlib only

---

## 🚀 Usage

```bash
./OConvertX
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*

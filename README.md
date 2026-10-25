# 🦉 OChanHop

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-Security-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OChanHop** — part of the OwlSec Toolkit.

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OChanHop uses a Wi-Fi site survey you have already collected (BSSID, SSID, channel, RSSI, width) to plan a clean channel layout. It scores how busy and congested each channel is, recommends the best channel per band and builds a scan dwell plan. It works offline and never transmits on a radio.

---

## ✨ Features

- Site-survey analyzer with a per-channel interference and utilisation score
- Best-channel recommendation for 2.4, 5 and 6 GHz plus a scan dwell plan
- Channel maps for 2.4 / 5 / 6 GHz, including DFS and 6 GHz PSC channels
- Regulatory-domain reference and compliance checks (FCC, ETSI, MIC and more)
- Findings graded A+ to F with MITRE ATT&CK mapping
- Reports in TXT / JSON / Markdown / CSV / SARIF

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OChanHop                                   # interactive menu
./OChanHop --analyze survey.csv --domain EU
./OChanHop --channels
./OChanHop --demo
```

Run `./OChanHop --help` for the full list of options.

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*

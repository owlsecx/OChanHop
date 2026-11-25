# 🦉 OChanHop

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-Security-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-orange?style=flat-square"/>
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

This tool is part of the **OwlSec** suite — a collection of 275+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

Proprietary — © 2026 Owlsec LLC. All rights reserved.

*Tools are distributed as pre-built executables. Source code is proprietary.*

---

## 🔍 Verification & Transparency

This tool is closed-source. These files let you see exactly what is inside it,
without the source:

- [`SBOM.cdx.json`](SBOM.cdx.json) — CycloneDX inventory: SHA-256 of this
  binary, the Go toolchain version it was built with, and every bundled
  component with its exact version and license. Feed it to Grype, Trivy or
  Dependency-Track to audit our dependencies for CVEs yourself.
- [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md) — the full license text
  of every third-party component, extracted from this binary.

Release signing, GPL compliance and vulnerability reporting:
[**TRUST.md**](https://github.com/owlsecx/owl-os/blob/main/TRUST.md)

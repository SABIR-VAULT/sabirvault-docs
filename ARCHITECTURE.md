# 🏛️ SABIR VAULT — System Architecture Overview

**Enterprise Neuro-Symbolic Forensic Platform**  
*Runtime: Python 3.11+ | Perception: Local 9B Vision-LLM | Kernel: Deterministic*

*Version 5.0.0-ENTERPRISE | August 2026*

---

## 📐 High-Level Architecture

```text
500+ Raw Documents (PDF, DOCX, Photos, Scans, XLSX)
                        │
                        ▼
┌─────────────────────────────────────────────────────────────┐
│ 📥 SECURE INGESTION GATEWAY                               │
│ • Archive unpacking (ZIP, RAR, 7z)                        │
│ • Antivirus quarantine & sandbox protection               │
└─────────────────────────────────────────────────────────────┘
                        │
                        ▼
┌─────────────────────────────────────────────────────────────┐
│ 👁️ LOCAL 9B MULTIMODAL PERCEPTION                         │
│ • OCR, handwriting, stamp detection                       │
│ • Native Excel parsing (0.1s, no OCR)                     │
│ • AI strictly for reading only                            │
└─────────────────────────────────────────────────────────────┘
                        │
                        ▼
┌─────────────────────────────────────────────────────────────┐
│ 🧮 DETERMINISTIC FORENSIC KERNEL (10,400+ lines)          │
│ • Entity resolution & deduplication                       │
│ • Graph theory & concentric rings topology                │
│ • Constitutional invariants enforcement                   │
└─────────────────────────────────────────────────────────────┘
                        │
                        ▼
┌─────────────────────────────────────────────────────────────┐
│ 🛣️ INVESTIGATION ROUTE ENGINE (6 Tracers)                 │
│ • Financial, corporate, and fraud detection               │
│ • Autonomous narrative construction                       │
└─────────────────────────────────────────────────────────────┘
                        │
                        ▼
┌─────────────────────────────────────────────────────────────┐
│ 👤 HUMAN-IN-THE-LOOP WORKBENCH                            │
│ • Lawyer verification (2-3 min)                           │
│ • 1-click anchor & relationship validation                │
└─────────────────────────────────────────────────────────────┘
                        │
                        ▼
              📄 Interactive Dashboard + Evidence Audit Trail
```

---

## 🧩 Forensic Subsystems

| Subsystem | Purpose | Key Feature |
|-----------|---------|-------------|
| 📥 **Secure Intake Gateway** | File extraction & security validation | Zip-Bomb defense, ClamAV |
| 👁️ **Document Perception** | OCR, handwriting, stamp recognition | 9B Vision-LLM, autofocus |
| 👑 **Entity Resolution Core** | Deduplication & relationship mapping | Levenshtein graphology |
| 🛡️ **Constitutional Guards** | Non-negotiable legal rule enforcement | Corporate non-biology, incest block |
| 👵 **Hidden Beneficiary Detection** | In-law chain & proxy identification | Score-based routing (≥4) |
| 🛣️ **Investigation Router** | Multi-step narrative construction | 6 autonomous tracers |
| 💸 **Anti-Fraud Radar** | Transaction & cashflow analysis | Structuring, round-trip detection |
| 📜 **Debt & Promissory Analysis** | Unbacked liability detection | Pre-bankruptcy timing |
| 🏃 **Asset Tracing** | Below-market asset sale identification | <30% value, 90-day window |

---

## 💻 Technology Stack

| Layer | Technology | Details |
|-------|------------|---------|
| 👁️ **Perception** | 9B Vision-LLM | Local inference, Apple Metal / CUDA |
| 🧮 **Kernel** | Python 3.11+ | Graph Theory, NetworkX, NumPy, OpenCV |
| 🔐 **Security** | Sandbox + ClamAV | AES-256-GCM, SHA-256 seals |
| 💻 **Hardware** | Apple Silicon / x86_64 | Mac mini M2 (16GB) / Enterprise Server |
| ⚡ **Power** | 15W operational | 17h battery backup (EcoFlow 256Wh) |
| 🌐 **Network** | None required | 100% Air-Gapped / Zero-Cloud |

---

## 🌍 Multi-Jurisdictional Support

| Country | Registries | Key Legal Framework |
|---------|------------|---------------------|
| 🇺🇦 **Ukraine** | EDR, RNOKPP | Family Code Art. 260 |
| 🇺🇸 **USA** | IRS, UCC, Delaware LLC | Community Property |
| 🇩🇪 **Germany** | Handelsregister, BGB | § 873 Grundbuch, § 1565 |
| 🇵🇱 **Poland** | KRS, NIP/PESEL | Kodeks Rodzinny |
| 🇰🇿 **Kazakhstan** | BIN/IIN, ТОО | Local registry |

> ⏱️ **New jurisdiction added in 15 minutes** — declarative JSON config, zero code changes.

---

## ⚡ Key Metrics

| Metric | Value |
|--------|-------|
| 🤖 **Automated Checks** | 376+ per commit |
| 🧪 **Unit Tests** | 199 in 0.84s |
| 🧮 **Formally Proven States** | 141 |
| 🛰️ **Behavioral Satellites** | 32 |
| 📊 **Benchmark Documents** | 800 |
| ⚡ **Power Consumption** | 15W |
| 🔒 **Runtime** | Air-Gapped / Zero-Cloud |
| 🏎️ **Per-Document Speed** | ~40 seconds |

---

## 📊 Competitive Advantage

| Feature | Conventional AI | SABIR VAULT |
|---------|----------------|-------------|
| **Verification** | Sample-based | ✅ Formal Proof by Exhaustion |
| **AI Role** | Generates opinions | ✅ Reading only (no decisions) |
| **Hallucinations** | High | ✅ Zero |
| **Security** | Cloud API | ✅ Air-Gapped / Zero-Cloud |
| **Extensibility** | Code changes | ✅ Declarative JSON configs |
| **Evidence** | Unverifiable | ✅ SHA-256 + Blockchain |

---

## 🔗 Related Documentation

- 📜 **[Verification White Paper](./VERIFICATION_WHITEPAPER.md)** — Formal proofs & benchmark results
- 📦 **[Changelog](./CHANGELOG.md)** — Release notes & milestones
- 🛡️ **[Security Model](./SECURITY.md)** — Zero-Trust architecture & compliance
- 🚀 **[Roadmap](./ROADMAP.md)** — Product roadmap & timeline

---

© 2026 SABIR VAULT. All rights reserved.  
Confidential Enterprise Documentation.

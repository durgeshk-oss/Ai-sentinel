# 🛰️ SENTINEL // AI: Workstation Signal Intelligence Matrix

[![Python Version](https://img.shields.io/badge/Python-3.11%2B-blue?logo=python&logoColor=white)](https://www.python.org)
[![Framework](https://img.shields.io/badge/Streamlit-1.32%2B-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io)
[![License](https://img.shields.io/badge/License-Apache%202.0-green.svg)](https://opensource.org/licenses/Apache-2.0)
[![Author](https://img.shields.io/badge/Author-Durgeshkumar%20Nonare-orange)](https://github.com)
[![Certs](https://img.shields.io/badge/CISSP%20%7C%20CISM%20%7C%20ISO%2027001%20%7C%20CTIA%20%7C%20CCNA%20%7C%20CCNP-certified-cyan)](https://github.com)

> **Continuous Workstation Signal Intelligence & Leak Isolation Vector**  
> *Transforms raw application telemetry into high-visibility cyber operational intelligence — entirely locally, with zero cloud connectivity.*

---

## 👤 Author

**Durgeshkumar Nonare**  
*GRC Architect · AI Cybersecurity Engineer · Program Manager*

| Certification | Domain |
|---|---|
| **CISSP** | Information Systems Security Professional |
| **CISM** | Information Security Management |
| **ISO 27001** | ISMS Lead Implementer / Auditor |
| **CTIA** | Certified Threat Intelligence Analyst |
| **CCNA** | Cisco Certified Network Associate |
| **CCNP** | Cisco Certified Network Professional |

Durgeshkumar is a multi-disciplinary cybersecurity leader with deep expertise spanning Governance, Risk & Compliance (GRC), AI-augmented security engineering, and enterprise-scale program management. He architects zero-trust security frameworks, drives SOC 2 / NIST SP 800-53 / GDPR compliance programs, and builds AI-native threat detection platforms that operate at the application tier — the layer traditional EDR tools are blind to.

SENTINEL // AI is a direct product of this expertise: a local-first, asynchronous endpoint protection matrix engineered to catch credential leaks, shadow AI usage, and data exfiltration vectors within sub-second detection windows — entirely offline, zero cloud exposure.

---

## 🔍 Overview

SENTINEL // AI is an asynchronous, application-tier endpoint protection matrix designed to ingest, classify, and visualize user-space telemetry and structural system risks in real time.

By replacing traditional, high-overhead kernel operations with a non-blocking ingestion loop, SENTINEL // AI converts raw application transactions, configuration drifts, and data exfiltration markers into a **high-visibility, dark-mode monitoring interface** with no external network calls and no cloud dependencies.

---

## ⚡ Core Features

| Feature | Description |
|---|---|
| **Continuous Signal Polling** | Background worker threads query local databases at configurable intervals — no manual refresh |
| **Animated AntPath Ingress Maps** | Moving neon laser tracer vectors map active threat trajectories on a global dark map |
| **Balanced 2×2 Grid UI** | Custom glassmorphism panels — severity donut stacked directly over live activity feed |
| **Real-Time Exfiltration Feed** | Streaming payloads categorized by severity in real time (CRITICAL / HIGH / MEDIUM / LOW / INFO) |
| **Forensic Audit Ledger** | Immutable, sortable historical log for compliance mapping and incident investigation |
| **AI Semantic Taxonomy Engine** | Model-agnostic classification converts unstructured log strings into normalized structured fields |

---

## 🗺️ System Architecture

```
[ LOCAL APPLICATIONS ]  ──►  [ ASYNC INGEST PIPELINES ]  ──►  [ SQLITE TRANSACTION MATRIX ]
                                                                          │
[ HIGH-CONTRAST OPS ROOM ]  ◄──  [ CUSTOM CSS LAYOUT GRID ]  ◄──  [ PLOTLY / FOLIUM ENGINES ]
```

| Layer | Component | Responsibility |
|---|---|---|
| **1 — Data Source** | Local Apps · DB Logs · Agent Telemetry | Raw event emission |
| **2 — Ingestion Matrix** | Async Pipelines · SQLite Interface | Thread-safe normalization |
| **3 — Analytics Engine** | State Handler · Plotly · Folium | Severity scoring & chart compilation |
| **4 — Presentation Grid** | HTML5/CSS3 · AntPath Animation | Dark-mode ops room rendering |

---

## 🛠️ Technology Stack

| Layer | Technology | Purpose |
|---|---|---|
| Language | Python 3.11+ | Typing, concurrency, data structures |
| Interface | Streamlit Framework | State caching, async hooks, multi-column layout |
| Geospatial | Folium + Leaflet AntPath | Animated vector trace path extensions |
| Analytics | Plotly Express | Dark-theme SVG/WebGL optimized rendering |
| Storage | SQLite3 | Atomic, thread-safe write-heavy transactions |

---

## 🔐 Detection Rule Engine

| Rule ID | Trigger | Severity |
|---|---|---|
| `TRAFFIC-LOG` | Local AI query transaction captured | INFO |
| `RULE-AI-CLASSIFIED` | Source code with credentials detected | CRITICAL |
| `RULE-AI-CLASSIFIED` | Internal infrastructure details detected | HIGH |
| `MODEL-INTEGRITY` | GGUF/safetensors file — no matching SHA-256 checksum | CRITICAL |
| `SHADOW-AI-PROC` | Inference process spawned outside approved list | MEDIUM |
| `NETWORK-EGRESS` | LLM API call from process in /tmp or Downloads | HIGH |

### Risk Scoring Formula (CVSS-Inspired, 0–10)
```
Score = (Confidentiality_Impact × 0.35)
      + (Data_Sensitivity       × 0.30)
      + (Model_Provenance_Trust × 0.20)
      + (Process_Legitimacy     × 0.15)

≥ 7.0  → IMMEDIATE ALERT
4.0–6.9 → WEEKLY BATCH REVIEW
< 4.0  → LOG ONLY
```

---

## 📊 Performance Benchmarks

| Metric | Result | Condition |
|---|---|---|
| Detection Latency | **< 1 second** | Credential exposure sub-second isolation |
| Max CPU Footprint | **< 1.8%** | Verified under active data streams |
| UI Page Jumps | **0** | Custom CSS fade-in eliminates all flashes |
| Message Throughput | **> 100 msg/sec** | Async non-blocking engine benchmark |
| Fade-in Animation | **600ms** | Smooth polling loop transition |

---

## 🔐 Security & Compliance

**Zero-trust architecture model** — all telemetry parsing in protected user-space isolation zone.

| Framework | Control Reference | Implementation |
|---|---|---|
| SOC 2 Type II | Trust & Confidentiality | Continuous automated tracking; immutable event ledger |
| NIST SP 800-53 | SI-4, CA-7 | App-tier inspection mapping config drifts & exfiltration |
| GDPR Article 32 | Security of Processing | Immediate localization of credential/key exposures |
| ISO/IEC 27001 | A.12.4, A.16.1 | Structured event taxonomy with forensic audit chain |
| EU AI Act | Art. 9, 13, 17 | Shadow AI detection, model provenance, AI usage audit trails |

---

## 📦 Installation

```bash
# 1. Clone the repository
git clone https://github.com/portfolio/sentinel-ai-core.git
cd sentinel-ai-core

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Initialize database schema
sqlite3 sentinel_local.db < data/mock_telemetry_schema.sql

# 5. Launch the dashboard
streamlit run src/interface/dashboard_app.py
```

Dashboard available at `http://localhost:8501`

---

## 📁 Repository Structure

```
sentinel-ai-core/
├── .github/workflows/lint-and-validate.yml   # CI quality pipelines only
├── assets/
│   ├── system_architecture_matrix.png        # Conceptual architecture diagram
│   ├── dashboard_preview.png                 # Sanitized UI screenshot
│   └── moving_map_demo.gif                   # UI animation preview
├── config/public_app_manifest.json           # Schema parameters (no tokens)
├── data/mock_telemetry_schema.sql            # Empty table definitions
├── src/
│   ├── core/
│   │   ├── database_handler.py               # Query compilation modules
│   │   └── telemetry_aggregator.py           # Data normalization abstractions
│   ├── interface/
│   │   ├── custom_css_theme.py               # Glassmorphism overrides
│   │   └── dashboard_app.py                  # Main UI (sanitized)
│   └── main.py                               # Execution entry point
├── .gitignore
├── LICENSE
└── requirements.txt
```

---

## 🔭 Roadmap

| Phase | Timeline | Initiative |
|---|---|---|
| **Phase 1** | Short-Term | Webhook alert engines → enterprise SIEM integration |
| **Phase 2** | Mid-Term | eBPF network probes → socket-level capture |
| **Phase 3** | Long-Term | Edge quantized ML → offline hardware-accelerated inference |

---

## 🛑 Security & IP Disclaimer

> **This public archive is explicitly sanitized for portfolio display.**
>
> It intentionally omits: internal orchestration patterns · proprietary regex classification matrices · agent decision models · active system configuration tokens · production-tier baseline configurations

All telemetry streams shown in previews are **simulated for demonstration purposes only**.

---

## 📄 License

Distributed under the **Apache 2.0 License**. See [`LICENSE`](LICENSE) for details.

---

## 📬 Contact

**Durgeshkumar Nonare** — GRC | AI Cybersecurity | Program Manager  
CISSP · CISM · ISO 27001 · CTIA · CCNA · CCNP

[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)](https://github.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com)

---

*SENTINEL // AI — Bridging the application-tier visibility gap at the workstation boundary.*

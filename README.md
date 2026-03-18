# IntelNewsWorkflow

A single-file HTML reference document for **sub-news OSINT and CTI (Cyber Threat Intelligence) collection**. Designed for analysts monitoring threat actors, conflict zones, organized crime, and state-sponsored activity across open sources including social media, Telegram, vendor blogs, and government advisories.

## Overview

`sub_news_intel_workflow_v2.html` is a self-contained, offline-capable operational reference. Open it in any browser — no server, no dependencies, no installation required.

---

## Sections

### 01 · Workflow
- **Collection Workflow** — 5-step process: define requirement → select sources → collect/log → triage → escalate or discard
- **Collection Plan Template** — structured fields per active track (track name, priority tier, standing requirement, sources, refresh cadence, confidence threshold, owner)
- **Triage Decision Gate** — pass/escalate/discard rules table based on source tier, corroboration, and recency
- **Source Tier System** — four-tier trust hierarchy:
  - `T1` — Primary / Official (government, courts, official releases)
  - `T2` — Established Secondary (vetted research-grade outlets)
  - `T3` — Community / OSINT (quality-variable)
  - `T4` — Adversarial / Unverified (treat as RUMINT by default)

### 02 · Term Lists
Curated keyword banks for search and monitoring across three domains:
- **Cartel / OCG Terms** — organized crime group names, plaza terms, operational indicators
- **APT / State Actor Terms** — threat group aliases, campaign names, malware families, TTPs
- **Conflict Zone Terms** — unit designations, geographic markers, operational vocabulary (multilingual)

### 03 · Sources
- **Additional Source Registry** — categorized table of vetted sources across: wire services, threat intel vendors (Mandiant, SentinelLabs, Volexity, MSTIC, etc.), conflict monitors (ISW, ACLED, Borderland Beat, InSight Crime), government advisories (CISA, CERT-UA, UK MoD), and OSINT tooling (Maltego, Shodan, Censys, TGStat, Ransomwatch)

### 04 · Search Dorks
Pre-built search operator templates for:
- APT campaign / new vendor reporting
- APT zero-day / active exploitation
- APT C2 infrastructure (Shodan)
- Ransomware leak site / eCrime activity
- Cartel incident — plaza-level (Spanish-language)
- OFAC sanctions / designations
- Russia-Ukraine frontline (ISW + OSINT)
- DPRK crypto theft / sanctions evasion
- Iran proxy operational activity
- Africa / Wagner successor activity
- GitHub — leaked credentials / actor tooling
- Telegram channel discovery (TGStat)

### 05 · Cadence
Recommended collection schedule broken into four rhythms:
| Cadence | Time | Focus |
|---|---|---|
| **Daily** | 30–60 min | RSS sweep, Telegram check, CISA/CERT-UA alerts, Google Alert digest, ransomwatch scan |
| **Weekly** | 60–90 min | Run dorks, vendor blog review, cartel sweep, ACLED pull, corroboration pass, delta briefs |
| **Monthly** | 2–4 hrs | Full actor profile update, source audit, Maltego refresh, Shodan/Censys sweep, knowledge gap analysis |
| **Triggered** | On major event | RUMINT confirmation/disconfirmation pass, confidence re-rating, source fidelity recalibration |

### 06 · Follows & Channels
- **X / Twitter Follow List** — categorized accounts: government/official, CTI vendors, conflict/OSINT, cartel/crime reporting
- **Telegram Priority Channels** — channels organized by domain with tier designations and monitoring notes

---

## Usage

1. Download `sub_news_intel_workflow_v2.html`
2. Open in any modern browser (Chrome, Firefox, Edge)
3. Use the sticky nav bar to jump between sections
4. Print-friendly layout supported (`Ctrl+P` / `Cmd+P`)

---

## Intended Audience

- OSINT analysts and CTI researchers
- Threat intelligence teams building collection workflows
- Conflict monitors and investigative researchers
- Anyone operating a structured open-source monitoring operation

---

## Disclaimer

This document contains terminology, source lists, and search operators related to threat actors, organized crime, and active conflict zones — for **research and defensive intelligence purposes only**. T4/RUMINT sources listed are monitored for signal, not trusted for reporting. Establish personal exposure management protocols before expanding Telegram monitoring — graphic content is standard in cartel and conflict channels.

---

*v2 — Updated search dork library, expanded source registry, four-tier cadence model*

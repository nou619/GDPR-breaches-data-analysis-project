# BreachWatch EU

```
██████╗ ██████╗ ███████╗ █████╗  ██████╗██╗  ██╗    ██╗    ██╗ █████╗ ████████╗ ██████╗██╗  ██╗
██╔══██╗██╔══██╗██╔════╝██╔══██╗██╔════╝██║  ██║    ██║    ██║██╔══██╗╚══██╔══╝██╔════╝██║  ██║
██████╔╝██████╔╝█████╗  ███████║██║     ███████║    ██║ █╗ ██║███████║   ██║   ██║     ███████║
██╔══██╗██╔══██╗██╔══╝  ██╔══██║██║     ██╔══██║    ██║███╗██║██╔══██║   ██║   ██║     ██╔══██║
██████╔╝██║  ██║███████╗██║  ██║╚██████╗██║  ██║    ╚███╔███╔╝██║  ██║   ██║   ╚██████╗██║  ██║
╚═════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝     ╚══╝╚══╝ ╚═╝  ╚═╝   ╚═╝    ╚═════╝╚═╝  ╚═╝
```

> **338 incidents. 27 countries. €20M on the line. This is what EU data breaches actually look like.**

---

## What is this?

**BreachWatch EU** is a GDPR-focused breach intelligence report built on the VCDB (Veris Community Database) validated dataset. It answers three questions every security and compliance team should already know the answer to:

1. **Who** is getting breached across EU member states
2. **How** attackers are getting in
3. **What data** is at risk — and what that means under GDPR

This isn't a vendor whitepaper. It's real incident data, mapped to real regulatory obligations, presented in a format that works for both technical teams and boardrooms.

---

## The Numbers

| Metric | Value |
|--------|-------|
| Total incidents analysed | **338** |
| Confirmed data theft rate | **72%** |
| EU member states covered | **27** |
| Peak year | **2013** (78 incidents) |
| Most breached country | **Ireland** (61 incidents) |
| Max GDPR fine exposure | **€20M or 4% global turnover** |
| Art.33 notification window | **72 hours** |

---

## Slides

| # | Module | What it covers |
|---|--------|----------------|
| 01 | `SYS_INIT` | Title & key stats |
| 02 | `MODULE_00` | GDPR legal framework — Art.33, Art.34, Art.83 |
| 03 | `MODULE_01` | Scale of the problem |
| 04 | `MODULE_02` | Geographic exposure by member state |
| 05 | `MODULE_03` | Attack vectors — how breaches happen |
| 06 | `MODULE_04` | Data types stolen — what's actually at risk |
| 07 | `MODULE_05` | Temporal trends 2010–2025 |
| 08 | `MODULE_06` | Sector risk matrix |
| 09 | `MODULE_07` | Recommendations tied to GDPR obligations |
| 10 | `END_OF_REPORT` | Closing summary |

---

## GDPR Obligations at a Glance

```
ART. 33  ─────  72-hour breach notification to supervisory authority
ART. 34  ─────  Direct notification to affected individuals if high risk
ART. 32  ─────  Appropriate technical & organisational security measures
ART. 25  ─────  Privacy by design and by default
ART. 9   ─────  Special categories (health, biometric, genetic data)
ART. 83  ─────  Fines up to €20M or 4% of global annual turnover
```

---

## Top Findings

**Hacking dominates.** 54% of all incidents (181 of 338) were external hacking attacks — mostly via credential theft, web app exploitation, and unpatched systems. This is an Art.32 failure at scale.

**Ireland leads the breach count.** Not because Irish companies are less secure — because Dublin is the EU headquarters for Meta, Google, Apple, Twitter, and most major US tech firms. Where the HQ is, the DPC notification goes.

**Human error is 1 in 4 breaches.** 86 incidents were caused by staff mistakes — misconfigured databases, emails sent to wrong recipients, lost devices. Art.29 and Art.32 both speak directly to this. Training and DLP tooling are not optional.

**Medical data is the highest-risk category.** 36 incidents involved health data — Art.9 special category. Every single one of those required DPO involvement and near-automatic Art.34 victim notification. There is no "assess and decide" with health data.

**GDPR worked. Then hacking came back.** Incident volume dropped sharply after May 2018 enforcement. By 2025, hacking is surging again — 15 incidents already — suggesting Art.32 compliance is still surface-level at many organisations.

---

## Recommendations

### `01` Harden Against Hacking — `ART.32` — `CRITICAL`
Deploy MFA across all systems. Run quarterly web app pentests. Implement credential monitoring and alerting. This is the single highest-impact action given 54% of breaches originate here.

### `02` Eliminate Human Error — `ART.29 + ART.32` — `HIGH`
Mandatory data handling training for all staff. DLP tooling to catch misrouted emails and accidental disclosures. Email classification labels. Art.29 is explicit: processors must act only on controller instructions.

### `03` Protect Personal & Medical Data — `ART.9 + ART.25` — `HIGH`
Encrypt personal data at rest and in transit. Apply data minimisation — don't store what you don't need. Automate Art.33 breach detection workflows so the 72-hour clock doesn't run out while someone is writing an incident report.

---

## Data Source

All figures are drawn from the **VCDB (Veris Community Database)** — a community-maintained, schema-validated dataset of real-world security incidents. Filtered to EU member states only. Covers 2010–2025.

VCDB uses the **VERIS framework** (Vocabulary for Event Recording and Incident Sharing) developed by Verizon, the same methodology behind the annual DBIR report.

> This report does not include incidents where EU jurisdiction could not be confirmed. Numbers are conservative.

---

## Built With

- `pptxgenjs` — presentation generation
- VCDB validated incident dataset
- GDPR Regulation (EU) 2016/679
- Too much coffee

---

## License

This report is for internal use and educational purposes. VCDB data is available under a Creative Commons license. GDPR is, unfortunately, mandatory.

---

```
// The patterns are consistent.
// The obligations are clear.
// The next step is action.
```

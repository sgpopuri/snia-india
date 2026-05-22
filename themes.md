# India Differentiator Themes

> The twelve themes that anchor SNIA India content. Each one answers `T-IND-02` from [`charter.md`](charter.md): *"why is this **India's** SNIA story, not a re-run of US content?"*
>
> Eight themes are **in scope** for 2026-27; four are **deferred** with a watch-brief. Theme IDs are stable. Every artifact in [`roadmap.md`](roadmap.md) tags one or more theme IDs.

---

## In-scope themes (8)

### T-01 — India Stack at population scale `[in-scope]`

**Why India.** India is the only country running an open, government-mandated, vendor-neutral digital public infrastructure at population scale (1.4 B IDs, 18+ B UPI transactions/month). The storage requirements — consent ledger, transactional resilience, multi-jurisdictional residency — cannot be sourced from US-based reference architectures.

**The gap.** SNIA's existing transactional storage references assume Western payment volumes (~10 B/month at peak), Latin scripts, single-tenant compliance. India operates 5-7× the volume across 22 scripts under overlapping regulators (DPDP / RBI / SEBI / IRDAI).

**Owners.** Sriram Popuri (lead), Vinoth Velayutham (BFSI lens), Rahul Nema (multi-script angle).

**Anchor partners.** NPCI (Vishal Anand Kanvaty), EkStep (Pramod Varma), iSPIRT (Sharad Sharma, Siddharth Shetty), MOSIP (Ramesh Narayanan), UIDAI.

**Deliverables.** `P-03` India Stack podcast (Apr 2027); chapter in `R-01` annual report.

### T-03 — Sovereign storage & DPDP/RBI/SEBI/IRDAI compliance `[in-scope]`

**Why India.** No other major economy has four overlapping sectoral regulators with statutory, fineable data residency / log retention / encryption / breach reporting mandates landing simultaneously in 2024-2026. DPDP Rules 2025 carry ₹250 cr penalty per breach.

**The gap.** US/EU SNIA content treats data sovereignty as a regulatory abstraction (GDPR is the only model). India needs a domain-specific reference for DPDP + RBI + SEBI + IRDAI + CERT-In overlapping mandates.

**Owners.** Vinoth Velayutham (lead), Sunil Kumar (data-protection lens), Karnendu Pattanaik (governance).

**Anchor partners.** Trilegal (Rahul Matthan), MeitY, RBI, Justice (Retd.) B.N. Srikrishna, KPMG (Akhilesh Tuteja).

**Deliverables.** `W-02` DPDP webinar (Feb 2027); `B-04` Q&A blog; inputs to WP-01; chapter in `R-01`.

### T-04 — Consent-tagged storage primitives `[in-scope]`

**Why India.** DEPA (Data Empowerment & Protection Architecture) and the Account Aggregator framework are India-originated abstractions where consent is a first-class data object. ABDM's HIE-CM applies the same to health records. Consent as a storage-layer attribute exists nowhere in published standards.

**The gap.** Storage standards (CDMI, S3, NFSv4, POSIX) treat metadata as opaque to access control. Consent-tagged retention, erasure, and sharing at the storage layer has no reference.

**Owners.** Vinoth Velayutham (lead), Sriram Popuri, Sunil Kumar.

**Anchor partners.** iSPIRT (Siddharth Shetty), MOSIP (Ramesh Narayanan), Trilegal, ABDM Office, Sahamati.

**Deliverables.** `TWG-01` India-led TWG charter — *Sovereign Storage Primitives* (Jun 2027). White paper deferred to year 2 (post-TWG charter ratification).

### T-06 — IndiaAI cluster reference architecture `[in-scope]`

**Why India.** The IndiaAI Mission empanelled 38,231 GPUs across 14 sovereign cloud providers but did **not** specify a parallel-FS, checkpoint, or shared object-store standard. Fragmentation is already visible.

**The gap.** SNIA Storage.AI (US-led) addresses accelerator-attached primitives (AiSIO, GPU Direct Bypass) but does not anchor a population-scale sovereign-cloud reference architecture for India's specific deployment landscape.

**Owners.** Sriram Popuri (lead, WP-01), Mohan Parthasarathy (CXL/memory tier), Rahul Nema (orchestration), Sunil Kumar (data-reduction).

**Anchor partners.** CDAC (Hemant Darbari), Yotta (Sunil Gupta), Jio (Sayed Peerzade), E2E (Tarun Dua), Krutrim, Sarvam, Bhashini, MeitY.

**Deliverables.** `WP-01` white paper (Public Review Jun 2027); `P-02` podcast (Nov 2026); `S-05` India-named Storage.AI deliverable; chapter in `R-01`.

### T-08 — Logging-as-regulation `[in-scope]`

**Why India.** CERT-In's 180-day log retention directive, DPDP Rule 6, and RBI's audit log requirements together convert log storage from an ops concern into a compliance object with statutory penalties. No US framework treats logs this way.

**The gap.** SNIA Security TWG addresses TLS, KMIP, PQC — useful but tangential to the *retention SLA* problem. Indian operators need a "DPDP-ready log retention reference."

**Owners.** Sunil Kumar (lead), Vinoth Velayutham (BFSI lens), Dnyaneshwar Pawar (cost angle).

**Anchor partners.** CERT-In, RBI, KPMG (Akhilesh Tuteja), Druva (Jaspreet Singh).

**Deliverables.** Chapter in WP-01; chapter in `R-01`.

### T-09 — CXL 4.0 in production `[in-scope]`

**Why India.** With HBM3e/HBM4 sold out through 2026 and Indian sovereign clouds locked into H100/H200/B200 SKUs, CXL is the practical lever to cut $/token and grow effective memory. India is a structurally larger CXL adopter per dollar of GPU than the US.

**The gap.** CXL Consortium content is vendor-driven. India needs a CIO-facing, vendor-neutral "what to procure, deploy, and validate" view.

**Owners.** Mohan Parthasarathy (lead), Aadish Kuvelker (fabric side).

**Anchor partners.** CXL Consortium (via Mohan); HPE / Dell / Astera / Samsung / Marvell India; IIT Bombay CASPER; IISc CSA; IIT Madras CSE.

**Deliverables.** `W-01` CXL webinar (Aug 2026); `B-02` Q&A blog; `W-03` KV Cache webinar (May 2027).

### T-10 — Multi-script Indic datasets `[in-scope]`

**Why India.** India is building petabyte-scale Indic-language training datasets (Bhashini, AIKosh, AI4Bharat IndicCorp). Tokenizer-aware chunking, normalised scripts, and language-tagged residency differ structurally from Latin-only object storage.

**The gap.** Hugging Face / Common Crawl reference architectures assume Latin scripts. Multi-script object storage with downstream LLM/RAG consumption has no published storage-layer reference.

**Owners.** Rahul Nema (lead), Sriram Popuri.

**Anchor partners.** Bhashini (Amitabh Nag), AI4Bharat (IIT Madras), IISc DREAM:Lab (Yogesh Simmhan).

**Deliverables.** `P-04` podcast (Aug 2027); `B-07` blog; year-2 joint paper with IISc/IIT.

### T-12 — Tokens-per-watt sustainability `[in-scope]`

**Why India.** India's grid pressure (peak summer demand exceeded 250 GW in 2025; data-centre demand growing 30%+ YoY) makes tokens-per-watt a CFO-level conversation. SNIA Emerald v5 is the standardised methodology for the storage piece.

**The gap.** Sustainability-as-marketing dominates; Emerald-grade quantification of storage power per inference token in real Indian deployments is undocumented.

**Owners.** Sunil Kumar (lead), Dnyaneshwar Pawar (data-reduction angle).

**Anchor partners.** Dell India (Vamsi Vankamamidi), MeitY data-centre policy, IndiaAI Mission, NASSCOM (Sangeeta Gupta).

**Deliverables.** Chapter in `R-01` annual report. Year-2 dedicated webinar.

---

## Deferred themes (4) — watch-brief only

These have technical merit but are deferred to year 2 to maintain cadence (`T-IND-06`). Each is monitored; at most one panel mention or backup-blog in year 1.

### T-02 — Sovereign cloud architecture `[year-2]`

Heavily overlaps with T-03 (DPDP compliance). Treated as a sub-theme in year 1. Standalone webinar in year 2 once DPDP enforcement evidence (penalty notices, audits) is mature. **Watch-brief owner:** Vinoth.

### T-05 — Frugal storage economics `[year-2]`

Cross-cutting; covered in WP-01 reference architecture. Dedicated year-2 white paper on data-reduction economics for INR-denominated AI clouds. **Watch-brief owner:** Dnyaneshwar.

### T-07 — Fabric: UEC vs RoCE for India clouds `[year-2]`

UEC v1.0 launched Jul 2025 with Indian interest, but deployments are early. Premature for year 1 webinar. **Watch-brief owner:** Aadish.

### T-11 — Agentic AI storage primitives `[year-2]`

Specifications (MCP Memory Pattern, Anthropic Memory Tool, Claude persistence) still maturing. Year-2 white paper target. **Watch-brief owner:** Rahul Nema, Sriram.

---

## Theme-to-differentiator matrix

Cross-check that the eight in-scope themes cover all four India differentiators from [`charter.md`](charter.md).

| Theme | India Stack | Sovereignty / Reg | Academia | IndiaAI Mission |
|---|---|---|---|---|
| T-01 India Stack | ●●● | ●● | ● | ● |
| T-03 DPDP compliance | ● | ●●● | — | ●● |
| T-04 Consent-tagged storage | ●●● | ●●● | ● | ● |
| T-06 IndiaAI cluster ref arch | ● | ●● | ● | ●●● |
| T-08 Logging-as-regulation | ● | ●●● | — | ● |
| T-09 CXL 4.0 | — | ● | ●● | ●●● |
| T-10 Multi-script Indic datasets | ●●● | ● | ●●● | ●●● |
| T-12 Tokens-per-watt | — | ●● | ● | ●●● |

Every column has at least one ●●● anchor. Coverage check passes.

## Versioning

| Version | Date | Change |
|---|---|---|
| 0.1 | 2026-05-22 | Initial 12-theme map. 8 in scope, 4 deferred. For TC + Board review at next joint review; theme add/drop is a consensus decision. |

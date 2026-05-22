# Standards-Track Engagement & SDC India

> Two linked tracks that build the credibility SNIA India needs: (1) contributing to global SNIA TWGs and (2) earning the right to host SDC India. This file operationalises `T-IND-03` (standards-track contribution beats commentary) and `T-IND-07` (SDC India is the test) from [`charter.md`](charter.md).

---

## Part 1 — TWG Engagement Plan

### Why TWG seats matter more than podcasts

- **Credibility with sponsors.** SDC India sponsors will ask "what are you contributing to global SNIA?" The answer must name a TWG seat, a Public Review comment thread, and an authored deliverable.
- **Recruitment.** Indian engineers in GCCs want to know SNIA India is a path to global standards work.
- **Skip the podcast trap.** A chapter that produces only podcasts about other people's standards is a fan club. A chapter with TWG seats is an authoring node.

### Year-1 commitment

- Two existing TWGs joined with Indian named seats.
- One India-led TWG charter drafted and submitted.
- Quarterly Public Review comment quota — at least 1 substantive comment per TWG per quarter.
- Goal: India is **named** on at least one Storage.AI deliverable by Q3 2027.

### TWG 1 — Storage.AI

Storage.AI launched August 2025 as SNIA's open initiative for storage primitives that accelerator-attached AI workloads need. 15 founding members (AMD, Cisco, Dell, IBM, Intel, KIOXIA, Microsoft, NetApp, Pure Storage, Samsung, Seagate, Solidigm, Western Digital). NVIDIA is *not* on the founding list — this gives the initiative a vendor-neutral path.

Four anchor specifications: **AiSIO** (accelerator-attached I/O), **GPU Direct Bypass / OASIS**, **Flexible Data Placement (FDP)**, **NVMe IP-based KV (NIKV)**.

**India contributors:**

| Contributor | Focus | Quarterly comment target |
|---|---|---|
| **Sriram Popuri** (lead) | AiSIO; GPU Direct Bypass for sovereign clouds | 1 comment / quarter |
| **Mohan Parthasarathy** | CXL/SDXI cross-cut; FDP placement | 1 comment / quarter |
| **Rahul Nema** | NIKV; orchestration integration | 1 comment / quarter (from Q1 2027) |
| **Dnyaneshwar Pawar** (observer) | Data-reduction lens on tiered placement | Tracks specs; comments as needed |

**Engagement timeline:**

- Q3 2026: Membership applied. Sriram + Mohan + Rahul Nema named.
- Q4 2026: Attend SDC 2026 Santa Clara (28-30 Sep). Produce trip-report blog.
- Q1 2027: File first Public Review comments on AiSIO and FDP.
- Q3 2027: **Goal `S-05`:** India named on a Storage.AI deliverable.

**India-specific framings to contribute:**
- Sovereign-cloud reference architecture (Theme T-06) — AiSIO validated against IndiaAI Mission deployments.
- Multi-script Indic dataset object-store layout (Theme T-10) — FDP placement for tokenizer-aware datasets.
- DPDP-aware retention attributes (Theme T-03) — retention/erasure metadata as a first-class object attribute.

### TWG 2 — Computational Storage

Active Public Review specs: CSAPM v1.0.6, Computational Storage API v1.0.10.

**India contributors:**

| Contributor | Focus | Quarterly comment target |
|---|---|---|
| **Aadish Kuvelker** (lead) | Marvell silicon perspective on CSAPM; FC-attached computational storage | 2 comments / quarter |
| **Manjeet Kumar** | Mindteck SAN integration perspective | 1 comment / quarter |

**Engagement timeline:**

- Q3 2026: File TWG membership. Aadish + Manjeet named.
- Q4 2026: **Goal `S-03`:** First Public Review comment filed.
- Q1-Q3 2027: Continue comment cadence. Aadish to seek a sub-task lead role.

### Light-touch TWG liaisons

Not full seats, but monitored for Public Review opportunities:

- **Security TWG** — Vinoth monitors KMIP, Key Per I/O, PQC-readiness for DPDP.
- **Green Storage / Emerald v5** — Sunil monitors; relevant to tokens-per-watt (T-12).
- **Cloud Storage / CDMI 3.0** — Rahul Nema monitors; relevant to Indic datasets and consent-tagged extensions.

Each liaison commits to at least one substantive Public Review comment per year.

### India-led TWG charter — *Sovereign Storage Primitives*

Submitted to SNIA US TC by **30 June 2027** (`TWG-01`). Charter ratification target Q3 2027 — in time for SDC India to feature it.

**Why this is the right India-led TWG:**
- Topic India uniquely owns (consent-tagged storage, federated retention, jurisdictional residency).
- Cross-cuts existing TWGs (Cloud Storage, Security, Storage.AI FDP) without duplicating.
- Has anchor users (MOSIP, Sahamati, ABDM, Bhashini).

**Charter scope:**
- Consent-tagged retention — storage objects carry first-class consent attributes.
- Time-bound TTL enforcement with cryptographic proof of erasure.
- Signed-payload replication across federated nodes.
- Regulator-attestable audit logs (for CERT-In, RBI, SEBI, DPDP).
- Jurisdictional-residency tagging in the placement engine.

**Out of scope (initial).** Identity protocols, payment protocols, application-level consent UX.

**Proposed leadership:** Vinoth Velayutham (Chair), Sriram Popuri (Vice-Chair).

**Charter timeline:**

| Milestone | Target date | Owner |
|---|---|---|
| Draft circulated to TC | Apr 2027 | Vinoth |
| External review (iSPIRT + MOSIP) | May 2027 | Vinoth + Mohan |
| TC + Board sign-off | Jun 2027 | Mohan + Piyush |
| Submit to SNIA US TC | Jun 2027 | Mohan (TC Head) |
| SNIA US TC review | Jul-Sep 2027 | SNIA US TC |
| Charter ratification target | Oct 2027 | SNIA US Board |

**Pre-conditions:** At least 3 external endorsements from anchor users. Letter of support from at least 2 existing SNIA TWGs. TC + Board sign-off.

### Public Review comment quotas

| Contributor | TWG | Q3 2026 | Q4 2026 | Q1 2027 | Q2 2027 | Q3 2027 |
|---|---|---|---|---|---|---|
| Sriram | Storage.AI | apply | ramp | 1 | 1 | 1 + milestone |
| Mohan | Storage.AI | apply | ramp | 1 | 1 | 1 |
| Rahul Nema | Storage.AI | apply | — | 1 | 1 | 1 |
| Aadish | CS TWG | apply | 2 | 2 | 2 | 2 |
| Manjeet | CS TWG | apply | 1 | 1 | 1 | 1 |

Mohan (TC Head) chairs a **monthly TWG sync** (30 min, last Friday) where each contributor reports activity and the India-led TWG charter is incrementally drafted.

---

## Part 2 — SDC India Runway

### What SDC India was

| Year | Format | Attendance |
|---|---|---|
| 2018 | 1-day in-person, Bengaluru | ~150 |
| 2019 | 2-day in-person, Bengaluru | ~250 |
| 2022 | Virtual (single-day) | Limited momentum |
| 2023-26 | No event | Dormant |

### What SDC India will be

> **Note (May 2026).** Given the late program start, the SDC India target is pushed from the original Dec 2026 announcement to **mid-2027 announcement**, with the event in **late 2027 or H1 2028**. This is more realistic and preserves credibility.

- **Format.** 2 days in-person + 1-day virtual (hybrid).
- **Location.** Bengaluru (target).
- **Attendance target.** 300-400 in-person + 500 virtual.
- **Tracks (5).** Sovereign AI Storage / Consent-tagged Storage & DPI / Computational Storage & Fabric / CXL & Memory Disaggregation / Industry.

### Quarterly checkpoints

| Quarter | Milestone | Owner | Go/no-go |
|---|---|---|---|
| Q4 2026 | TC vote to commit; Board endorsement; informal sponsor soundings | Mohan + Piyush | <8 of 9 TC yes → downscale to virtual |
| Q1 2027 | Formal SNIA US Board proposal; venue scouting (4+ venues) | Piyush + Mohan | US Board approval required for credibility |
| Q2 2027 | SNIA US Board approval; venue down to 2; sponsor pitch v1 | Khushboo + Sameer | Approval is pre-condition for sponsor asks |
| Q3 2027 | **Sponsor commitments locked** (4 Premier + 6 Technology); **public announcement** at W-04 webinar | All | <3 Premier → fallback to virtual edition |
| Q4 2027 / Q1 2028 | Program Committee; CFP opens; sponsor contracts signed | Mohan (chair) + Sriram (agenda) | |
| Q2 2028 | CFP closes; agenda finalised; registration opens | Sriram | ≥80 submissions target |
| **Q3 2028** | **SDC India runs** (fallback: late 2027 if everything tracks ahead) | Full TC + Board | |

### Sponsor architecture

| Tier | Slots | Indicative INR | Target sponsors |
|---|---|---|---|
| Premier | 4 | ₹35-45 L | Dell, NetApp, IBM, HPE |
| Technology | 6 | ₹15-22 L | Western Digital, Marvell, Mindteck, Calsoft, NVIDIA India, Yotta |
| Track | 4-6 | ₹5-8 L | Druva, Krutrim, Sarvam, Hasura, Yugabyte |
| In-kind | open | — | NASSCOM, iSPIRT, CDAC, IIT/IISc |

**Target sponsor revenue:** ~₹3.0 cr. **Indicative cost:** ~₹1.6-2.3 cr. **Net surplus** funds student scholarships, Indian Storage PhD Prize, and next year's program.

### Critical pre-conditions for "go" announcement

All of the following must be true before announcing SDC India:

- [ ] ≥4 Premier sponsors committed
- [ ] ≥6 Technology partners committed
- [ ] Venue selected (LOI signed)
- [ ] SNIA US Board has formally approved
- [ ] WP-01 ratified by SNIA TC
- [ ] At least one India-named TWG deliverable

If pre-conditions are not met, the announcement is reframed as "save-the-date." If still unmet after 6 months, fallback is **SDC India: Virtual Edition**.

### Venue plan

Bengaluru is the target city. Three candidate categories:

- **Commercial hotel** (Sheraton Grand / Conrad / ITC Gardenia) — predictable scale (300-500), higher cost (~₹40-60 L).
- **Sponsor-hosted** (Microsoft Garage / NetApp / HPE campus) — lower cost, but vendor-neutrality disclosure required. Capacity ~150-250.
- **Academic** (IISc / IIT auditorium) — strong academic signal, supports T-IND-05. Capacity ~200-300.

**Recommended:** Commercial hotel as primary (predictable, sponsor-friendly). Academic hosting for SDC India 2029 once chapters are established.

### Program Committee

Formed after SDC India announcement. Composition:

- **Chair:** Mohan Parthasarathy (TC Head).
- **Agenda Chair:** Sriram Popuri.
- **TC reviewers:** Full TC.
- **Academic reviewers (≥2):** Yogesh Simmhan (IISc), Biswabandan Panda (IIT Bombay).
- **Industry reviewers (≥2):** Sunil Gupta (Yotta), Sayed Peerzade (Jio).
- **SNIA US TC liaison:** One member nominated by SNIA US TC.

Target: **30-40 sessions across 5 tracks**, plus 12 student presentations and 6 keynote slots.

## Versioning

| Version | Date | Change |
|---|---|---|
| 0.1 | 2026-05-22 | Initial TWG engagement plan + SDC India runway. Adjusted timeline: SDC India pushed to late 2027/H1 2028 from original Dec 2026 announcement. For TC + Board review. |

---
title: "Pharmaport: QMS — drafting log"
tags: []
url:
date_created: 2026-10-09 14:13
citekey:
author:
year:
type:
updated: 2026-10-09 14:46
---
[< back to Pharmaport MoC](pharmaport-map-of-content.md)

One section per document. For each: what is **law** (cited) vs. **our choice** (to confirm), the placeholders, and open points. Croatian files live in `~/Documents/pharmaport/05_qms/`; the generator and content sources are in `05_qms/_izvor/` (`node build.js SOP-xx.js` rebuilds a .docx).

---
## Conventions used across all documents (set in SOP-SK-01)

| Convention | Law or choice? |
|---|---|
| Croatian language, not handwritten, clear and unambiguous | **Law** — EU GDP 4.2 |
| SOPs approved, signed and dated by the responsible person | **Law** — Prav. čl. 25(2) |
| Version control; old versions withdrawn from workplaces | **Law** — Prav. čl. 25(7); EU GDP 4.2 |
| Every page: company, title, code, version, effective date, "page x of y"; approval table on page 1; change history at end | Choice (standard practice) |
| Numbering: PK / POP / ORG / ORM / OD / PL / SOP-SK·NP·SKL·RK·TR·PU / RU / OB | Choice — maps to [SOP master list](pharmaport-sop-master-list.md) groups B·C·D·E·F·G |
| Quality manual signed by RP **and** director; org chart and job descriptions signed by director | Choice — grounded in EU GDP 1.1 ("Za sustav kvalitete odgovorna je uprava") and 2.2 (management appoints the RP) |
| Two-year periodic review | **Choice** — EU GDP 4.2 only says "redovno revidirati i ažurirati", with no interval |
| Format: .docx, A4, Arial | Choice — your vault convention puts deliverables in the work folder as docx |

---
## SOP-SK-01 Upravljanje dokumentacijom i zapisima — v01 NACRT (2026-10-09)

File: `05_qms/SOP-SK-01_Upravljanje-dokumentacijom-i-zapisima_v01_NACRT.docx` (5 pages)

**Every legal requirement mapped to where it sits in the SOP:**

| Requirement (source) | SOP section |
|---|---|
| Documentation system covering SOPs, instructions, contracts, records, paper or electronic; available, clear, unambiguous — Prav. čl. 25(1) | 1, 2, 5.1 |
| SOPs approved and signed by the RP with date — čl. 25(2) | 3, 5.3(e) |
| Other documents approved, signed, dated by an authorised person — čl. 25(3) | 5.3(e) |
| Corrections signed + dated, original legible, **reason stated** — čl. 25(4) | 5.7(c) |
| Available to authorities on request — čl. 25(5) | 5.4 |
| Retention ≥ 5 years — čl. 25(6); EU GDP 4.2 | 5.9 |
| Version control; obsolete versions removed — čl. 25(7); EU GDP 4.2 | 5.5 |
| Records made at the time of the action, time clearly shown, traceable — čl. 25(10); EU GDP 4.2 | 5.7(a) |
| Electronic records: access protection, integrity checks, backups ≥ 5 y on a separate site — čl. 24(1)–(3); EU GDP 3.3.1 | 5.8 |
| Croatian, not handwritten, room for manual entries — EU GDP 4.2 | 5.3(b) |
| Easy access for every employee — EU GDP 4.2 | 5.4 |
| Personal data deleted/anonymised once no longer needed — EU GDP 4.2 | 5.9 |
| Safety-features (FMD) technical-problem records: "barem godinu dana nakon isteka roka valjanosti lijeka ili pet godina nakon što je lijek stavljen u prodaju" — NN 126/19 čl. 11(2) | 5.9 |
| Change control system — EU GDP 1.2 | 5.3(a) → SOP-SK-04 |
| Records of delegated duties — Prav. čl. 9(4) al. 8 | 3 |

**Internal choices to confirm:**
1. Two-year periodic review (5.6).
2. Retention clock starts when a document is superseded or a record is created (5.9). The law says only "ne smije biti kraće od 5 godina", without saying from when.
3. Paper record rules: no correction fluid or pencil, single strike-through, "N/P" for unused fields (5.7(b)–(c)). Standard GMP/GDP practice, not in the Croatian texts.
4. Approval: in practice the RP will be both author and approver, because the company has two people. The table still lists both roles. The director signs "Upoznat" (acknowledged) on SOPs — a choice, not required.
5. Electronic distribution is read-only from a document store (5.4).

**Placeholders [●]:** names (RP, director), effective date, document storage system, archive location.

**Conflict noted, resolved in favour of the stricter rule:** EU GDP 4.2 says the reason for a change should be recorded "prema potrebi" (where appropriate). Prav. čl. 25(4) requires it **always** ("navodeći razlog izmjene"). The SOP follows the Pravilnik.

**Gap:** the EU GDP cites Directive 95/46/EZ for personal data. I didn't name the current data-protection law in the SOP ("u skladu s propisima o zaštiti osobnih podataka"), because I haven't pulled a source for it.

**Still to draft for this SOP:** Prilog 1 (the template — effectively the docx layout itself), OB-SK-01-01/02/03 forms. Proposed: do these together with POP-01 once the PK-01 structure is agreed.

---
## PK-01 Poslovnik kakvoće — v01 NACRT, part 1 (chapters 1–6), 2026-10-09

File: `05_qms/PK-01_Poslovnik-kakvoce_v01_NACRT.docx` (7 pages; chapters 7–14 are headings marked "u izradi"). Signed by RP **and** director (the director's name is taken from the court extract).

**Law → where it sits:**

| Requirement (source) | PK section |
|---|---|
| Quality manual or equivalent; QS description + SOP list for the application — Prav. čl. 7(2), 64(1) t. 11; EU GDP 1.2 | 1 |
| EU GDP apply via Prav. čl. 6 (which cites the superseded 2013/C 68/01) | 1 (note in the text) |
| Wholesale = buying, receipt, storage, sale, supply, bringing in from / sending to other EU states — ZoL čl. 3 t. 77; Prav. čl. 4(1) | 3.1 |
| Parallel import only after a HALMED authorisation — ZoL čl. 130; parallel distribution only after EMA approval + written notice to HALMED ≥ 15 days before entry — Prav. NN 38/20 čl. 2(2)–(4) | 3.1 |
| Original manufacturer packs only; products authorised in HR/EU or parallel import/distribution — Prav. čl. 5(1) | 3.2 |
| Product groups for the licence — Prav. čl. 64(1) t. 4, čl. 66 | 3.2 table |
| Suppliers licensed and checked — ZoL čl. 117; Prav. čl. 27–28 · Customers only per ZoL čl. 118(1); Prav. čl. 29; EU GDP 5.3 | 3.3 |
| Domestic supply obligation — ZoL čl. 120(1) al. 6; supply "u najkraćem mogućem roku" — čl. 118(2) | 3.3 |
| Management responsible for the QS, appoints the RP, provides resources — EU GDP 1.1, 1.2, 2.2; Prav. čl. 7(1), 9(3) | 4.1, 5.2 |
| Measured quality objectives, reviewed by management — EU GDP 1.4 (i)–(ii) | 4.2 |
| Organigram + written job descriptions incl. delegation — Prav. čl. 10(2); EU GDP 2.3 | 5.1 |
| RP qualification: mag. pharm. + ≥ 2 years — ZoL čl. 3 t. 87; employed — Prav. čl. 9(1); GDP knowledge — čl. 9(2) | 5.3.1 |
| Personal performance, constant availability, delegate tasks not responsibility, job description defines authority — Prav. čl. 9(3) | 5.3.2 |
| RP duty list — Prav. čl. 9(4) (all 10 indents, verbatim), plus batch release čl. 31, SOP approval čl. 25(2), national extras EU GDP 2.2 xii | 5.3.3 |
| Named person for complaints — čl. 39(1); for recalls — čl. 45(1); for out-of-hours deliveries — čl. 55 | 5.4 |
| Enough qualified staff; workload not a quality risk — Prav. čl. 10(1), (3) | 6.1 |
| Training: initial + continuous, written programme, falsified medicines, special handling, records, effectiveness — Prav. čl. 11(1)–(4); EU GDP 2.4 | 6.2 |
| Hygiene programmes; no food/drink/tobacco/own medicines in storage — Prav. čl. 12, čl. 20(2); EU GDP 2.5 | 6.3 |

**Our choices — please confirm or change:**
1. **Scope exclusions (3.1):** no third-country import/export, no brokering (the registered activity includes *posredovanje*, but that needs a separate brokering licence — Prav. čl. 68), no repackaging. Matches the parallel-trade plan; *interventni uvoz* not mentioned at all, as agreed.
2. **Product-group table (3.2)** — my **proposal**, pending Q15. **DA:** EU-authorised medicines at room temperature. **NE:** narcotics/psychotropics, blood products, radiopharmaceuticals, medical gases, investigational products, non-EU-authorised medicines. **[●] still open:** cold chain (8–15 °C and 2–8 °C) and immunologicals. Every **DA** adds SOPs and inspection scope; every **NE** limits what you can trade.
3. **Quality policy wording (4.1)** — eight commitments. Legally the policy just has to exist and be owned by management (EU GDP 1.1); the content is ours.
4. **Quality objectives and targets (4.2)** — all ours. Only the **annual recall test** is law (Prav. čl. 45(2)). Placeholders: recall trace time, complaint closing days, CAPA on-time %.
5. **"Management may not influence the RP's quality decisions" (5.2, last bullet)** — not in the law. It protects her independence, and inspectors look for it. Keep?
6. **Management review at least once a year (5.2)** — EU GDP 1.4 says only "periodičnog".
7. **She holds all three named roles (5.4)** — complaints, recalls and the responsible person herself. Unavoidable with two staff.

**Placeholders [●]:** her name; location of the activity (Q9); licence details (after grant); company phone/email (Q12); her hours and how availability is ensured (Q3 — HALMED letter); **how availability is covered during her annual leave or sick leave**; out-of-hours delivery persons (5.4).

**🟧 Risk flagged by drafting 5.3.2 — absence cover.** Prav. čl. 9(3) requires the RP to be *"stalno biti dostupna"* (constantly available). The Pravilnik has no deputy RP — I searched for "zamjen"; the only hits concern storage mix-ups and the occupancy permit. With one pharmacist, her holidays and sick leave are a gap the inspector will ask about. **Suggest adding question 2(e) to the HALMED letter:** how must availability be ensured while the responsible person is absent, and may a second pharmacist (e.g. under contract) be designated for that period?

**🟧 Risk — staffing (6.1).** Prav. čl. 10(1) requires "dovoljan broj stručnjaka … te drugo tehničko osoblje". With two people, this only works if a contracted warehouse supplies the technical staff (storage-contract route, Q9). With an own warehouse, Pharmaport would need to hire.

**Not yet drafted:** chapters 7–14. Chapters 8, 9 and 12 depend heavily on Q9 (own warehouse vs. contract). Chapters 7, 10, 11, 13 and 14 can be written now.

---
## PK-01 Poslovnik kakvoće — v01 NACRT, part 2 (chapters 7, 10, 11, 13, 14), 2026-10-09

File: same .docx, now 17 pages. Chapters 8 (outsourcing), 9 (premises) and 12 (transport) are still placeholders, waiting on Q9.

**New sources read in full for this part:** Pravilnik o obustavi stavljanja lijeka u promet i povlačenju lijeka iz prometa, NN 122/14 (17 articles + form). Pravilnik o vrsti podataka i načinu izrade izvješća o potrošnji lijekova, NN 122/14 (8 articles). No amendments to either (checked on HALMED's list and zakon.hr). Also ZoL čl. 62, 130–134.

**Law → where it sits:**

| Requirement (source) | PK section |
|---|---|
| QS with risk management, management involvement — Prav. čl. 7(1); four elements — čl. 8; what the QS must ensure (i–vi) — EU GDP 1.2 | 7.1 |
| Documentation — Prav. čl. 25; electronic records — čl. 24 | 7.2 |
| QRM definition — Prav. čl. 3 t. 3; proportionality, ICH Q9 — EU GDP 1.5; where risk assessment is required — Prav. čl. 23(2), 40(1), 53(2) | 7.3 |
| Change control — EU GDP 1.2; notify HALMED of changes — ZoL čl. 126(1) | 7.4 |
| Deviations + CAPA — EU GDP 1.2 (v)–(vi), 8.2; Prav. čl. 39(5), 52 | 7.5 |
| Management review content (i)–(v), documented and communicated — EU GDP 1.4 | 7.6 |
| Self-inspection programme, records, RP duty — Prav. čl. 52, 9(4); EU GDP 8.2 | 7.7 |
| Procedures fully described; identity; anti-falsification — Prav. čl. 26; EU GDP 5.1 | 10.1 |
| Supplier licence check + qualification + red flags — ZoL čl. 117; Prav. čl. 27–28; EU GDP 5.2 | 10.2 |
| Customer checks; unusual sales patterns — Prav. čl. 29; ZoL čl. 118; EU GDP 5.3 | 10.3 |
| Receipt — Prav. čl. 30; EU GDP 5.4 | 10.4 |
| Batch release by the RP per written procedure; check the batch-release evidence — Prav. čl. 31; EU GDP 5.4 | 10.5 |
| Safety features: verification and decommissioning; the 48-hour rule — ZoL čl. 120(1) al. 4; NN 126/19 čl. 8, 11(1) | 10.6 |
| Storage, segregation, FEFO, stock counts — Prav. čl. 32–34 | 10.7 |
| Destruction — Prav. čl. 35; contract — čl. 64(1) t. 12 | 10.8 |
| Remaining shelf life; delivery document content; out-of-hours deliveries — Prav. čl. 36, 37, 55 | 10.9 |
| Domestic supply — ZoL čl. 118(2), 120(1) al. 6 | 10.10 |
| Parallel import: no business link with the MAH — ZoL čl. 130(1); 15-day notice — čl. 131(1)–(2); report changes — čl. 134(1); parallel distribution — Prav. NN 38/20 čl. 2(3) | 10.11 |
| Transaction records (CoA removed by NN 146/22) — Prav. čl. 25(8)–(10); ZoL čl. 120(1) al. 2 | 10.12 |
| Complaints — Prav. čl. 39(1)–(5); EU GDP 6.2 | 11.1 |
| Returns, incl. the **30-day** window (NN 19/20) and cold-chain evidence — Prav. čl. 40–43 | 11.2 |
| Falsified medicines: tell HALMED "odmah" (immediately — ZoL čl. 120(1) al. 5); tell Ministry + MAH (Prav. čl. 44(1)); written notice within 24 h at the latest (NN 122/14 čl. 6(2)); segregate (čl. 44(2)) | 11.3 |
| Recall SOP + named person + annual test — Prav. čl. 45; recall plan — ZoL čl. 120(1) al. 1; start fast, customer data — EU GDP 6.5 | 11.4.1 |
| Notify HALMED of defects in **12 h / 24 h / 7 days** by class; 14-day report on measures — NN 122/14 čl. 6(1)–(4), čl. 12; Ministry too if the cause is a defect or falsification — Prav. čl. 48(3) | 11.4.2 |
| Hold stock in place during a suspension — NN 122/14 čl. 9; **the wholesaler that supplied the customers carries out the recall** — čl. 11(2); notify all customers of the batch — Prav. čl. 46; final report — EU GDP 6.5; disposal decision — Prav. čl. 48(4) | 11.4.3 |
| As parallel-import holder: initiate the recall, notify HALMED within 24 h — ZoL čl. 62(6) | 11.4.4 |
| Theft — Prav. čl. 43, 59(2) · Records — čl. 48(1)–(2) | 11.5–11.6 |
| Annual consumption report by **1 March**, ATC-classified, via HALMED's web app — NN 122/14 (potrošnja) čl. 2–3; ZoL čl. 141(1) | 13 |

**Our choices — please confirm or change:**
1. **Notifying HALMED of licence changes "before the change is made" (13).** ZoL čl. 126(1) sets no deadline. The table says so openly and adds our own practice.
2. **Shortage-system reporting listed as an obligation (13)**, although Q14 (whether it applies to an outward-only wholesaler) is still open. This follows my earlier recommendation to report anyway.
3. **Annual management review (7.6)** — same as part 1.
4. **Chapter 14 document list.** It adds **ORM-02 (job description — director)**, which wasn't in the master list. Rows marked [●] (storage SOPs) are either Pharmaport's own or replaced by the warehouse's, depending on Q9.

**Conflicts and ambiguities — presented, not resolved:**
- **A. Recall notice deadline for a parallel-import holder (11.4.4).** ZoL čl. 62(6): *"Nositelj odobrenja je o postupku … obvezan izvijestiti Agenciju najkasnije u roku od 24 sata od trenutka saznanja"* (must notify within 24 hours of learning of it). NN 122/14 čl. 6(2) gives **7 days** for Class III and 12 h for Class I. Also, the second sentence of čl. 62(6) says only "Nositelj odobrenja", without "za paralelni uvoz" — so it may refer to the marketing-authorisation holder alone. **The draft applies the stricter rule: 24 h for every class, 12 h for Class I.** → Q16.
- **B. Falsified medicine: "odmah" vs. 24 h.** ZoL čl. 120(1) al. 5 and Prav. čl. 44(1) say *odmah* (immediately). NN 122/14 čl. 6(2) gives 24 h for a suspected falsification. These don't conflict: notify immediately, and treat 24 h as the outer limit for the written notice. The draft says both.
- **C. "aktivnog statusa" in returns (11.2).** The 2020 amendment requires returned packs to be *"aktivnog statusa"* (of active status). The text doesn't define it. The most likely meaning is that the pack's unique identifier is still "active" in the safety-features repository — **my inference, not in the text**. Quoted verbatim in the PK. → Q17.
- **D. The annual-report regulation is based on ZoL čl. 187(3), not čl. 141(2).** Its substance is exactly the čl. 141(1) duty, so the PK cites both. It still says *"u kunama"* (in kuna) — the PK points to HALMED's format (its čl. 3(5)). → Q18.
- **E. What the recall regulation does *not* say.** It sets no deadline or method for notifying our own customers, gives no recall "levels", and requires no direct notice to the Ministry. Those come from the GDP Pravilnik (čl. 46–48) and EU GDP 6.5 via its čl. 6(3). The PK uses those sources and does not invent deadlines.

**HALMED letter:** question **2(e)** on absence cover has been added to `04_correspondence/2026-10_HALMED_upit-prije-podnosenja-zahtjeva_NACRT.txt`. It asks whether a second pharmacist, *employed* for the absence period, may stand in — employment is required by Prav. čl. 9(1).

---
## Related

[Pharmaport MoC](pharmaport-map-of-content.md)

# PROJECT STATE — Dog Behaviour Integration Study
> READ THIS FIRST at the start of every session.
> REWRITE the Status, Session Log and Next Action before finishing.
> Never assume memory from a prior session — this file IS the memory.

---

## Study Brief

Cross-country comparison of canine behaviour case rates in dogs living with humans.
**Goal:** Identify which countries have the highest success in dog-human household integration,
and determine what structural, legal, cultural, and environmental factors correlate with that success.

### Core Metrics (all must be sourced, none invented)
1. Behaviour-related shelter surrender/relinquishment rates
2. Reported dog bite incident rates (per capita where possible)
3. Referral rates to behaviour professionals / veterinary behaviourists
4. Supplementary verifiable metrics (insurance claims, euthanasia-for-behaviour rates)

### Study Parameters
- Timeframe: last 10 years (~2014–2024); flag sudden shifts and note possible causation
- Scope: countries where robust published data exists — do not force global coverage
- Output: peer-review style report, multi-section with charts, metrics shown separately AND combined
- Definition caveat: "behaviour case" definition varies by country — must be stated per dataset
- **Data integrity rule: NEVER invent data to fill gaps. State gaps explicitly.**

---

## Phase Tracker

| Phase | Name | Status |
|-------|------|--------|
| 0 | Setup & structure | ✅ Complete |
| 1 | Source discovery — per metric, per country | ✅ Complete (partial — see gaps) |
| 2 | Data extraction — per-country files | ✅ Complete for: USA, UK, Australia, Netherlands, Germany/Austria, Japan, Scandinavia |
| 3 | Cross-country compilation table | ✅ Drafted (cross-country.md populated — methodology note critical) |
| 4 | Variable collection (laws, density, breeding, culture) | 🟡 Partial — dog-trainer-regulation.md written; others pending |
| 5 | Analysis & correlation | ⬜ Not started |
| 6 | Draft report sections | ⬜ Not started |
| 7 | Validation pass | ⬜ Not started |
| 8 | Final output | ⬜ Not started |

---

## Countries in Scope — Status

| Country | Bite data | Surrender data | Referral data | Variables | Status |
|---------|-----------|---------------|---------------|-----------|--------|
| USA | ✅ Strong | ✅ Good | ❌ Gap | ✅ | In scope |
| UK (England) | ✅ Strong | ✅ Good | ❌ Gap | ✅ | In scope |
| Australia | ✅ Strong | ✅ Partial | ✅ Partial (11%) | ✅ | In scope |
| Netherlands | ⚠️ Old (2010) | ❌ Incomparable system | ❌ Gap | ✅ | In scope (qualitative) |
| Germany | ❌ Gap | ❌ Gap | ❌ Gap | ✅ | Phase 2 required |
| Austria | ❌ Gap | ❌ Gap | ❌ Gap | ✅ | Phase 2 required |
| Japan | ⚠️ Serious only | ❌ Gap | ❌ Gap | ⚠️ | Qualitative only |
| Scandinavia | ⚠️ Fatality only | ❌ Gap | ❌ Gap | ⚠️ | Phase 2 required |
| Canada | 🔍 Signposted | 🔍 Signposted | ❌ Gap | — | Phase 2 required |
| New Zealand | 🔍 Signposted | 🔍 Gap | ❌ Gap | — | Phase 2 required |
| France | 🔍 Eurostat only | ❌ Gap | ❌ Gap | — | Phase 2 required |

---

## Critical Methodological Finding (from Phase 1)
**Direct quantitative comparison across countries is severely constrained by:**
1. Different healthcare systems mean different thresholds for what counts as a "reported bite"
2. Shelter systems are architecturally different (no-kill vs open-admission; hokensho vs RSPCA model)
3. No country publishes a national behaviour referral rate
4. Behaviour as surrender reason is inconsistently coded across studies and countries

**The only truly comparable metrics found:**
- Hospital admission rates using ICD-10 W54 coding: UK and Australia are directly comparable
- USA ER visit data is comparable to itself over time but NOT to UK/Australia hospitalisation
- Eurostat fatality data (ICD-10 W54) allows European comparison but only for deaths

**This methodological limitation must be prominently stated in the Methods section.**

---

## Key Sudden Shifts Identified (flag in report)

| Country | Shift | Scale | Period | Likely causation |
|---------|-------|-------|--------|-----------------|
| UK | Fatal dog attacks | 2 → 20+ (800%+) | 2019–2023 | Pandemic puppy surge; XL Bully incidents; inexperienced owners |
| UK | Hospital admissions | +33% in 1 year | 2022/23–2023/24 | Same; also pandemic population reaching adolescence |
| UK | Dog population | +4.5M dogs | 2019–2022 | Pandemic acquisition |
| USA | Fatal dog attacks | avg 33 → avg 84/yr | 2005–2018 → 2020–2023 | Pandemic; off-property attacks ↑87%; pack attacks ↑ |
| Australia | Hospitalisation rate | 17 → 36.1/100,000 | 2013/14–2023/24 | Similar pandemic pattern; COVID spike 2020/21 confirmed |
| Austria | Owner education law | None → national mandatory | 2026 | Policy response to bite incidents / welfare concerns |
| Netherlands | BSL | Repealed | 2009 | Evidence review showed no bite reduction benefit |

---

## Session Log

### Session 1
- Date: September 2, 2026
- Completed: Full repo structure; Phase 1 research (web search systematic); country files for USA, UK, Australia, Netherlands, Germany/Austria, Japan, Scandinavia; cross-country comparison tables; data-sources registry; dog-trainer-regulation variable file; project state update
- Gaps found: Germany/Austria bite and shelter data; Scandinavian hospitalisation data; Japan post-2015 data; Canada; NZ; France; no country has publishable national behaviour referral rate
- **Next action: Phase 2 — targeted gap-filling. Priority: (1) Germany bite data via Destatis/Robert Koch Institut; (2) Canada via CIHI; (3) New Zealand via NZMJ 2019 paper; (4) Remaining variables files (population density, dog ownership rates, breeding regulation); (5) Literature search for Lower Saxony Sachkundenachweis outcome study**

---

## Files Written This Session

```
_PROJECT_STATE.md (this file)
data-sources.md (comprehensive)
data/by-country/USA.md
data/by-country/UK.md
data/by-country/Australia.md
data/by-country/Netherlands.md
data/by-country/Germany-Austria.md
data/by-country/Japan.md
data/by-country/Scandinavia.md
data/cross-country.md
variables/dog-trainer-regulation.md
```

---

## Session Protocol (follow every time)
1. Read this file — know exactly where you are
2. Read data-sources.md — check source status
3. Work the current phase
4. Update this file before ending (Session Log, Phase Tracker, Next Action)

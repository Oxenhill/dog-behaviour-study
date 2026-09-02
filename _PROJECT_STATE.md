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
| 2 | Data extraction — per-country files | ✅ Complete for: USA, UK, Australia, Netherlands, Germany/Austria, Japan, Scandinavia. 🟡 Partial for Canada (bite+shelter partially extracted); sources identified but NOT extracted for New Zealand and France (tool-limit blocked, see Session 2 log) |
| 3 | Cross-country compilation table | ✅ Drafted (cross-country.md populated — methodology note critical) |
| 4 | Variable collection (laws, density, breeding, culture) | 🟡 Substantial progress Session 2: population-density-and-ownership.md, breeding-regulation-and-ethics.md, breed-legislation-timeline.md all built in dated-timeline format; dog-trainer-regulation.md updated/corrected. Still missing: cultural-attitudes, public-space-access, veterinary-access, leash-laws, urban-vs-rural (see variables/README.md original list) |
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
| Canada | ⚠️ Old (2002-03) + small 2013-15 study | ✅ Extracted (2021, Humane Canada) | ❌ Gap | ⚠️ Density/ownership only | Qualitative/partial — see Canada.md |
| New Zealand | 🔍 Sources identified, NOT extracted (tool limit) | 🔍 Sources identified, NOT extracted | ❌ Gap | ⚠️ Density/ownership only | High priority next session — see New-Zealand.md |
| France | ✅ Fatality only (Eurostat, 79 deaths 1995-2016) + 🔍 ED severity study identified, NOT extracted | 🔍 SPA national study identified, NOT extracted | ❌ Gap | ⚠️ Density/ownership only | High priority next session — see France.md |

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

## Session 2 Methodological Decisions (locked in — apply going forward)

**1. Priority reordering:** Variables (Phase 4) now take priority over further country bite/surrender/referral gap-filling. Rationale: the study's actual goal (per original brief) is explaining WHY some countries integrate dogs into households more successfully — the metrics are the dependent variable, the Phase 4 variables (population density, dog ownership rate, breeding regulation/ethics, breed distribution, owner-education law) are the independent variables the whole analysis depends on. Build these out for the countries we already have metrics for (USA, UK, Australia, Netherlands, Germany/Austria, Japan, Scandinavia) before chasing more country-level metric gaps.

**2. Population-scope audit required on every source.** Original brief scope: "captive dogs that live with humans" only — excludes strays/free-roaming/community dogs. Most in-scope countries have negligible stray populations, but this must be verified per source, not assumed. Every entry in data-sources.md and every metric in the by-country files now carries a scope tag:
   - `[Scope: household-only]` — source explicitly restricted to owned/companion dogs
   - `[Scope: mixed/unclear]` — source doesn't specify, or plausibly includes non-household dogs
   - `[Scope: includes strays]` — source confirmed to include free-roaming/community dogs
   Any national bite/hospitalisation figure that mixes populations must be flagged before being used in cross-country comparison.

**3. NEW CORE METHODOLOGY PRINCIPLE — Temporal linkage (applies to all future variable and analysis work):**
   Metric data points span very different years across countries (Netherlands bite data ~2010; UK 1998–2024; Australia 2000–2024; Germany/Austria almost no historical metric data but a 2026 law just landing). It is a methodological error to compare a metric from year X against a country's *current* (2026) laws/practices. Instead:
   - Every Phase 4 variable file must be structured as a **dated timeline** (law/practice + effective date + change), not a current-state snapshot.
   - When a metric data point is used in analysis (Phase 5), it must be matched against the variable-state that was actually in effect during that metric's own collection window, not against present-day policy.
   - Where a country's law changed within the metric's own time series (e.g. UK pandemic dog surge + XL Bully ban 2024; NL BSL repeal 2009), the analysis must treat the series as segmented by regime, not as one flat average.
   - Causation notes (the "Key Sudden Shifts" table below) must be cross-checked against the variable timelines once built, not treated as freestanding commentary.
   This principle governs Phase 4 (in progress) and will govern Phase 5 (Analysis & correlation) — do not build a "current laws" table anywhere in this project.

**4. Canada / New Zealand / France:** One more focused search pass per country using the specific sources already identified (CIHI + Canadian Veterinary Journal for Canada; Mair et al. 2019 NZMJ + updates for NZ; INSEE/SPA/Eurostat for France), processed temporally (i.e. logged with the variable-state at the time of that data, not current law). If a country remains data-thin after this pass, it stays in the report as a qualitative/contextual entry with gaps explicitly stated — never silently dropped, never backfilled with invented figures.

---

## Session Log

### Session 1
- Date: September 2, 2026
- Completed: Full repo structure; Phase 1 research (web search systematic); country files for USA, UK, Australia, Netherlands, Germany/Austria, Japan, Scandinavia; cross-country comparison tables; data-sources registry; dog-trainer-regulation variable file; project state update
- Gaps found: Germany/Austria bite and shelter data; Scandinavian hospitalisation data; Japan post-2015 data; Canada; NZ; France; no country has publishable national behaviour referral rate
- **Next action: Phase 2 — targeted gap-filling. Priority: (1) Germany bite data via Destatis/Robert Koch Institut; (2) Canada via CIHI; (3) New Zealand via NZMJ 2019 paper; (4) Remaining variables files (population density, dog ownership rates, breeding regulation); (5) Literature search for Lower Saxony Sachkundenachweis outcome study**

### Session 2
- Date: September 2, 2026 (same day, continuation)
- User confirmed original study brief in full and answered 3 clarifying questions (see Session 2 Methodological Decisions above) before work began, per the project's "stop and ask if unsure" rule.
- Completed:
  - Population-scope audit added across data-sources.md and all 7 existing by-country files (household-only / mixed-unclear / includes-strays tags)
  - Three new dated-timeline variable files built: population-density-and-ownership.md, breeding-regulation-and-ethics.md, breed-legislation-timeline.md
  - dog-trainer-regulation.md updated with cross-references and a corrected Norway BSL entry (was "Pit Bull only", corrected to 6 breeds/types per Mattilsynet primary source)
  - Netherlands.md dog population figure corrected (~1M rough estimate → 1.7-1.8M, FEDIAF + Dibevo/NVG cross-checked)
  - Canada.md created: CHIRPP (1990-2003) + Halifax ED study (2013-15) bite data, Humane Canada 2021 shelter data (10% euthanasia, behaviour NOT isolated as a reason category) — retained as qualitative/partial-quantitative per the "don't force, don't drop" scope rule
  - New-Zealand.md and France.md created: strong candidate sources IDENTIFIED (NZMJ 2019 Mair et al. + 2022 follow-up; SPA France national abandonment study; a likely-INVS French ED severity study) but full-text extraction was blocked mid-session by a WebFetch tool-usage limit (reset ~18:20 UTC) — logged honestly as "identified, not extracted" rather than estimated, per the data integrity rule
  - data-sources.md fully updated with every new source from this session (bite/shelter/variable tables, Population Scope Audit section, Key Institutions list)
- **Gaps found this session:** Mair et al. 2019 (NZ) still not extracted despite being the prior session's named priority — blocked by tool limit, not by data unavailability. Same tool-limit issue blocked the French INVS and SPA sources. Manitoba BSL-effectiveness study (Canada) blocked by reCAPTCHA/403 errors across 4 different access routes. EU's 23 Apr 2026 cat/dog welfare rules found but robots.txt-blocked (europarl.europa.eu) — title/date only.
- **Next action, in priority order:**
  1. **Re-fetch the 3 named-but-blocked sources first, before any new research:** (a) Mair et al. 2019 NZMJ 132(1494):8-14 + the 2022 NZMJ follow-up (direct PDF URL already captured in New-Zealand.md), (b) the INVS-looking French ED severity PDF at recomedicales.fr (URL captured in France.md), (c) the SPA France national abandonment study PDF at la-spa.fr (URL captured in France.md)
  2. Try the Manitoba BSL study (Raghavan et al., PMID 22753529) via a fresh route — 4 access methods failed this session (PubMed/PMC recaptcha, Cureus 403, SafetyLit robots-timeout)
  3. Retry europarl.europa.eu for the April 2026 EU cat/dog welfare rules full text (robots-blocked this session, but this is a significant post-window development worth confirming)
  4. Once NZ/France are extracted, revisit the Session 2 Decision #4 scope call (keep/drop/footnote) for both, and complete Germany/Austria bite/shelter data (still a full gap — Destatis/Robert Koch Institut/Tasso e.V. not yet located in either session)
  5. Remaining Phase 4 variable files not yet started: cultural-attitudes.md, public-space-access.md, veterinary-access.md, leash-laws.md, urban-vs-rural.md (see variables/README.md's original list)
  6. Once Phase 4 is substantively complete, revisit cross-country.md (Phase 3) to incorporate the new variable timelines before starting Phase 5 (Analysis & correlation)

---

## Files Written This Session

### Session 1
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

### Session 2 (new files)
```
variables/population-density-and-ownership.md
variables/breeding-regulation-and-ethics.md
variables/breed-legislation-timeline.md
data/by-country/Canada.md
data/by-country/New-Zealand.md
data/by-country/France.md
```

### Session 2 (files edited, not created)
```
_PROJECT_STATE.md (this file — decisions + full rewrite)
data-sources.md (Population Scope Audit section added; new sources logged; Key Institutions updated)
data/by-country/USA.md, UK.md, Australia.md, Netherlands.md, Germany-Austria.md, Japan.md, Scandinavia.md (scope-audit notes added; Netherlands.md dog population figure also corrected)
variables/dog-trainer-regulation.md (cross-reference note + Norway BSL correction)
```

---

## Session Protocol (follow every time)
1. Read this file — know exactly where you are
2. Read data-sources.md — check source status
3. Work the current phase
4. Update this file before ending (Session Log, Phase Tracker, Next Action)

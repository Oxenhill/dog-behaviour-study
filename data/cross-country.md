# Cross-Country Comparison Tables
> Phase 3 compilation, originally. Tables 1-2 and the country-scope lists rebuilt/reconciled Session 11 (autonomous continuation) against every by-country and variable file produced through Session 11. Tables 3-4 remain thin/unpopulated by data availability, not by oversight -- see their own notes below for exactly why.
> ⚠️ Direct comparison is HEAVILY CAVEATED — see methodology note below.

## CRITICAL METHODOLOGY NOTE
Different countries measure dog bite harm differently:
- UK: NHS Hospital Episode Statistics — Finished Consultant Episodes (FCEs) — hospital admissions only
- Australia: AIHW National Hospital Morbidity Database — hospital admissions only (same ICD-10 coding)
- USA: CDC/WISQARS — ER visits OR hospitalizations tracked separately; total bites estimated by survey (not repeated since 2001–2003)
- Netherlands: Internet survey 2010 — ALL bites including minor, not hospital admissions
- Japan: Formal reporting of "serious incidents" to government only — severe undercount
- Scandinavia: Fatality data only from Eurostat ICD-10

**This means HOSPITALISATION RATE is the most comparable metric across UK, Australia and (partially) USA.**
Netherlands, Japan, and Scandinavia cannot be directly compared using the same metric.

---

## Table 1 — Dog Bite Hospitalisation/Medical Rates (best available per country)

| Country | Rate | Year | Metric definition | Source |
|---------|------|------|-------------------|--------|
| Australia | 36.1 per 100,000 | 2023/24 | Hospital admissions (ICD-10 W54, AIHW) | AIHW National Hospital Morbidity Database |
| UK (England) | ~22 per 100,000 | 2023/24 | Hospital admissions (HES FCEs) | NHS Digital |
| UK (England) | 14.99 per 100,000 | 2018 | Hospital admissions (HES FCEs) | Tulloch et al. 2021, Scientific Reports |
| USA | ~120 per 100,000 | 2022 | ER visits (NOT comparable to above) | CDC WISQARS / HCUP NEDS |
| USA | ~4 per 100,000 | 2022 | Hospitalizations only | HCUP; calculated |
| Netherlands | ~1.7 per 100,000 | ~2010 | Hospital admissions (estimated from survey) | Cornelissen & Hopster 2010 — OLD DATA |
| Europe avg (fatality) | 0.009 per 100,000 | 2016 | Deaths only (Eurostat ICD-10 W54) | Sarenbo & Svensson 2021 |
| Japan | ~3.4 per 100,000 | 2015 | Formally reported serious incidents only | Japan MoE — NOT comparable |
| New Zealand | 13.7 per 100,000 | 2014/15–2018/19 (5yr avg) | Hospital discharges (ICD-10-AM external cause codes, National Minimum Dataset) | Duncan-Sutherland et al. 2022, NZMJ (Session 11) |
| Germany (Berlin only) | 977 total incidents (raw count, not converted to a rate) | 2024 | Reported incidents of any severity (city district-office reports, NOT hospital admissions) | Berlin open-data bite CSV (Session 11) — deliberately left as a raw count rather than a per-100,000 rate: this study did not independently verify a Berlin population figure to divide by this session, and the metric definition (any reported incident, including non-injurious lunges) is on a much lower severity rung than the hospitalisation rows above regardless, so a computed rate would invite an apples-to-oranges comparison. Full breakdown in data/by-country/Germany-Austria.md. |
| Germany (national) | DATA GAP | — | — | Still not located as of Session 11 (Berlin is city-level only) |
| Canada (Manitoba, provincial) | 3.47 per 100,000 (pre-BSL) -> 2.84 (post-BSL) | 1984-2006 | Provincial dog-bite-injury-hospitalisation rate | Raghavan et al., via dogsbite.org secondary summary (Session 2/6) — **[quality: C for this extraction route -- primary text blocked across PubMed/PMC/Cureus/SafetyLit; the underlying peer-reviewed study is A-grade but this figure needs re-verification against the primary text before use in the final report without caveat]** |
| Canada (national, CHIRPP) | 1.57 per 100,000 | fiscal year 2002-03 | Hospitalisation rate, national injury-surveillance database | CHIRPP (Session 2) — **dated: pre-dates this study's 2014-2024 window by over a decade; not directly comparable to the UK/Australia/NZ modern figures above without a like-for-like update, which was not located as of Session 11** |
| France | Not a hospitalisation rate — see note | 2009-2011 (data collection) | ED-survey severity study (8 hospitals), NOT ICD-10-coded administrative data | InVS/Sante publique France, via data/by-country/France.md (Session 6) — 33 cumulative bite fatalities over a 20-year period preceding the study is the only count-type figure; no per-100,000 rate computed by the source, so none is fabricated here either |
| Italy (Sicily, regional only) | 0.648 per 100,000 (2012) rising to 1.162 per 100,000 (2021) | 2012-2021 | Hospitalisation rate, regional administrative data (SDO hospital-discharge coding) | Alberghina et al. 2023, Frontiers in Veterinary Science (Session 11) — **NOT a national rate (Sicily only), and roughly an order of magnitude lower than the UK/Australia/NZ national figures above -- likely reflects a different DBIH coding threshold rather than a genuine tenfold-lower reality; not yet confirmed, see data/by-country/Italy.md** |
| Scandinavia | DATA GAP | — | — | Phase 2 required |

**Comparable pair (hospitalisation-rate rung):** UK, Australia, and now New Zealand share ICD-10(-AM)-coded, hospital-based counting methodology, making these three the most directly comparable rows in this table. Australia (36.1) > UK (22.0, 2023/24 NHS figure) > New Zealand (13.7, 5-year average) — though the NZ figure is a multi-year average rather than a single most-recent year, and all three health systems code and route bite injuries somewhat differently in practice, so this ordering should be treated as indicative, not a precise ranking. New Zealand's per-year trend is itself rising sharply (2.43%/year over the study window, and roughly eightfold since 1979), a data point worth pairing with the UK/Australia trend directions if a "changing over time" table is built in Phase 5.

**USA ER visits (120 per 100,000)** are NOT comparable to UK/Australia hospitalizations — different severity threshold and healthcare routing.

---

## Table 2 — Behaviour-Related Surrender Rate (% of shelter surrenders/intakes)

| Country | Rate | Year | Metric definition | Source |
|---------|------|------|-------------------|--------|
| USA | 28% of owner surrenders | 2018–2023 | "Behaviour Issues" as primary reason, open-admission US shelter, n=2,836 | Kisley et al. 2024, Animals (MDPI) |
| USA | 40% of surrenders had ≥1 behavioural reason | 2000 | Any behavioural contribution, 12 shelters | NCPPSP Salman et al. 2000 |
| USA | 7.8% of all intakes | — | "Aggressive behaviour" specifically | ASPCA cited data |
| UK | 6.07% of surrender contacts | 2024 | "Unwanted behaviours" as stated reason | Dogs Trust Annual Report 2024 |
| UK | 34.2% of relinquishments | ~2008 | Any behavioural contribution to decision | Diesel et al. UK academic study |
| Australia | 12.2% of all surrenders | 2018 | Behavioural problems (RSPCA SA) | RSPCA SA 2018 |
| Australia | 15% | — | Behaviour as primary reason (Sunshine Coast) | Carter & Taylor, cited in PMC8532592 |
| Netherlands | DATA GAP | — | System incomparable (no-kill; no strays) | — |
| Japan | DATA GAP | — | Different system (hokensho) | — |
| Germany | DATA GAP (definitional, not absence of shelter data) | 2024 | Deutscher Tierschutzbund's national survey exists (see data/by-country/Germany-Austria.md, Session 7) but reports occupancy-pressure/capacity and qualitative drivers ("owner inexperience," "rising vet costs"), not a % isolating "behaviour" as a surrender reason the way the US/UK/Australia sources do | Deutscher Tierschutzbund May 2024 |
| France | DATA GAP (definitional, not absence of shelter data) | 2024 | SPA's national abandonment study exists (see data/by-country/France.md, Session 6) but categorises reasons as life-disruption/incapacity/unwanted-litters/allergies/financial-hardship, with no "behaviour problem" category isolated at all | SPA (Societe Protectrice des Animaux) 2024 |
| Canada | DATA GAP (definitional, not absence of shelter data) | 2021 | Humane Canada's national report exists (see data/by-country/Canada.md, Session 6) but foregrounds economic/veterinary-cost factors (>15% of relinquishments linked to inability to afford vet care) rather than isolating "behaviour" as its own category | Humane Canada 2021 |
| Austria | DATA GAP | 2011 (dated) / 2024 (regional only) | A national shelter-infrastructure study exists (Session 11) but does not report surrender reasons at all; two regional 2024 sources (Pfotenhilfe OO, Tierschutz Austria) cite cost/breeder-quality factors but are not national and do not isolate "behaviour" as a category | See data/by-country/Germany-Austria.md |

**Definitional-gap note added Session 11:** four of the countries marked DATA GAP above (Germany, France, Canada, Austria) are NOT actually missing shelter/surrender data -- each has real, national or near-national shelter statistics logged in its own by-country file. What they lack is a source that isolates "behaviour problem" as its own distinct surrender-reason category the way the US, UK, and Australian sources in this table do. This is a genuine cross-country DEFINITIONAL difference worth naming explicitly in the final report, not a research gap to keep chasing -- these four countries' shelter systems and/or their published statistics simply categorise surrender reasons differently (more economically/circumstantially focused), which may itself be a culturally-informative finding (e.g. whether a country's shelter-sector data infrastructure treats "behaviour" as a distinct, trackable category at all could itself correlate with how seriously behavioural support is institutionally prioritised) -- flagged as a Phase 5 discussion angle, not asserted as a conclusion here.

**Critical confounder note:**
- "Behaviour" as surrender reason is inconsistently defined — some studies code any behaviour mention; others only primary reason
- Economic pressures, housing, and lifestyle changes are confounders in all countries
- UK Dogs Trust 6.07% vs UK academic 34.2% reflect different methodological approaches, not contradictory realities
- Australia 12.2% (RSPCA SA) may reflect RSPCA's more careful coding vs survey-based studies

---

## Table 3 — Behaviour Referral Rate

| Country | Data available | Notes |
|---------|---------------|-------|
| USA | Case series only (1 university, 20yr, n=1,923) | No national rate |
| UK | Practice survey (Ireland, >50% refer) | No national rate |
| Australia | 11% of UB cases referred by vet to behaviourist/trainer | VetCompass primary-care study (PMC7918417) — best available figure |
| All others | DATA GAP | — |

**This metric is globally unavailable as a national rate. Australia (11% referral by attending vet) is the only published figure found.**

**What other countries have instead (none convertible to a national rate, logged here so the gap reads as thoroughly-searched rather than overlooked):** USA has a single-institution case series (1,923 cases, one university veterinary behaviour-referral service, 1997-2017 -- describes case COMPOSITION, 72.2% aggression/20.1% anxiety, not a referral RATE against the dog population); Ireland (cited under UK) has a practice survey where >50% of vets report referring, but no denominator against the national dog population; UK, USA, Canada, France, Netherlands, Scandinavia, Germany/Austria, Japan, New Zealand all explicitly state in their own by-country files that no national behaviour-referral rate is tracked. This is one of this study's thinnest Core Metrics (Core Metric 3) across the board, not just for the countries left blank in the table above.

---

## Table 4 — Composite Integration Score
> NOT YET POPULATED — requires Phase 5 analysis. Per this study's "never invent data to fill gaps" rule, no placeholder or estimated scores are entered below.
> Pending: data normalisation, weighting methodology, gap-filling strategy

**Why this table cannot yet be honestly populated (assessed Session 11):** a composite score needs, at minimum, all three of Table 1 (bite), Table 2 (surrender), and Table 3 (referral) for the same country in the same rough time window. Checking every country currently in this file against that bar: **Australia is the ONLY country with all three metrics populated** (bite 36.1/100,000 2023/24; surrender 12.2-15%; referral 11%). USA, UK, and Canada each have bite + surrender but no referral rate. New Zealand has bite only (no comparable national surrender-behaviour-category or referral figure located). Germany, France, Austria have surrender data but it is definitionally non-isolated for "behaviour" (see Table 2's definitional-gap note) and none has a national bite rate or referral rate. With n=1 country carrying a complete row, a "composite ranking" would not be a genuine cross-country comparison — it would be one country's score presented as if ranked against gaps. This table should stay unpopulated until either (a) Referral Rate (Core Metric 3, this study's thinnest metric) is found for at least 2-3 more countries, or (b) a future session makes an explicit, stated methodological decision to build the composite from only Bite + Surrender (dropping Referral), which would at least allow USA/UK/Australia/Canada to be scored — this is a real option, not yet decided, and should be a deliberate Phase 5 choice made and justified in the final report, not defaulted into silently.

| Country | Bite Score | Surrender Score | Referral Score | Composite | Rank |
|---------|-----------|----------------|----------------|-----------|------|
| — | — | — | — | — | — |

---

## Countries Confirmed In Scope (data sufficient for inclusion)
> **REBUILT Session 11 (autonomous continuation)** — this list previously still reflected an early Phase 1/2 compilation pass and had not been reconciled against every by-country file since. Ratings below reflect actual data richness as of Session 11 across this study's five Core Metrics (bite/hospitalisation, surrender rate, referral rate, behavioural-problem prevalence, management-culture variables) — NOT just bite+surrender as the original two-metric version of this list implied.

- ✅ USA — strong data across most metrics: bite (multiple metric types, though not a clean modern hospitalisation-only rate — see Table 1 caveats), surrender (multiple studies), behavioural-problem prevalence (Dog Aging Project, PLOS ONE owner-psychology study), management-culture variables extensively documented. Referral: case series only, no national rate.
- ✅ UK (England) — strong data: bite (two hospitalisation-rate figures), surrender (two studies, divergent methodology), urban/rural deprivation gradient (3x, NHS Digital), management-culture extensively documented. Referral: no national rate (practice-survey only, via Ireland).
- ✅ Australia — strongest single-country data in this study: the ONLY country with all of bite (36.1/100,000), surrender (12.2-15%), AND referral (11%) rates populated (see Table 4 note above), plus urban/rural gradient and a genuine owner-survey behavioural-problem prevalence study (RSPCA Queensland/PMC7600298).
- ✅ New Zealand (added Session 11) — strong data: national ICD-10-AM hospitalisation rate plus ethnicity/deprivation/regional gradients (Duncan-Sutherland et al. 2022), the strongest urban/rural-deprivation dataset in this study alongside the UK's. No surrender-behaviour-category or referral data located.
- ✅ Canada (upgraded Session 11 — was previously listed only under "Countries to Research") — has genuine data across multiple metrics: bite (CHIRPP national rate, dated to 2002-03; Manitoba provincial BSL study, quality-caveated secondary-source extraction); surrender (Humane Canada 2021, national, but definitionally does not isolate "behaviour" — see Table 2 note); a genuine C-BARQ comparative study (von Rentzell et al. 2022) plus a newly-identified second C-BARQ lead (Sorbie et al. 2025, not yet extracted); veterinary-cost-as-relinquishment-driver data (>15% of relinquishments, quantified). No referral rate or modern (2014-2024-window) national hospitalisation rate.
- ✅ France (upgraded Session 11 — was previously listed only under "Countries to Research") — has genuine data: a purpose-built ED-based bite-severity study (InVS/Sante publique France, 33 cumulative fatalities, breed-neutral severity-risk finding — a key strand of this study's management-culture-over-breed thesis); a national abandonment/shelter study (SPA 2024, definitionally does not isolate "behaviour" — see Table 2 note); leash-law/management-culture data from Session 4; a genuine on-target C-BARQ validation study identified (Besegher et al.) though RESOLVED-AS-BLOCKED for full-text extraction (Session 11). No hospitalisation-rate figure or referral rate.
- ⚠️ Germany/Austria — upgraded from the original "legislative data only" rating but still partial: Germany has city-level-only bite data (Berlin, 977 raw incidents 2024, not converted to a national rate) and a formally resolved-as-blocked national bite-rate gap; Austria has a vet-survey (271 vets) rating breed as the LOWEST-relevance aggression factor (a key management-culture-over-breed strand) plus a national shelter-infrastructure study (dated, 2011) and regional-only 2024 shelter data. Neither has a national bite rate, a behaviour-isolated surrender rate, or a referral rate. Extensive management-culture/training-uptake historical data (Austrian OKV series) is this pair's strongest contribution.
- ⚠️ Japan — upgraded from "qualitative only": now has two genuine C-BARQ-based data points (Nagasawa et al. 2011 factor-structure validation, 734 owners; Nagasawa et al. 2015 US-Japan behavioural comparison) though neither gives a prevalence percentage, and the originally-sought prevalence-focused paper (Konno/Ogata) remains blocked. Bite data remains a formally-reported-serious-incidents-only figure (Japan MoE, NOT comparable to hospitalisation rates). No surrender or referral data.
- ⚠️ Sweden — NEW rating, Session 11: a genuine C-BARQ-based breed-comparison dataset now exists (Asp et al. 2015 / Eken Asp 2015 thesis, 3,591 dogs) reporting subscale means rather than a prevalence percentage; pet-insurance-penetration figures exist but conflict between two low-quality sources (40%+ vs 80%). No bite, surrender, or referral data located for Sweden specifically (only Nordic-regional qualitative data, shared with Norway/Denmark).
- ❌ Netherlands — partial/thin: bite data old (2010, internet-survey-based, not hospital-admissions); shelter system stated as incomparable (no-kill framing); behavioural-problem prevalence and C-BARQ data confirmed as a genuine gap after a dedicated Dutch-language search (Session 11).
- ❌ Norway — thin: only shared Nordic qualitative professional-perspective data (with Sweden/Denmark); confirmed genuine gap for prevalence/C-BARQ data after a dedicated Norwegian-language search (Session 11); NMBU has an apparently ongoing unpublished survey (future watch item).
- ❌ Scandinavia (Denmark specifically has richer standalone data than "Scandinavia" as a bloc — see Denmark's own by-country file and its representative-sample prevalence/urban-vs-housing-type findings) — fatality data only at the bloc level; insufficient for bite/surrender comparison.
- ⚠️ Italy (NEW, opened Session 11 same continuation) — a single regional (Sicily) bite-hospitalisation dataset now exists (0.648->1.162 per 100,000, 2012-2021), but it is not national and its comparability to the UK/Australia/NZ figures is flagged as unconfirmed (see Table 1 note). No shelter/surrender, behavioural-prevalence, or management-culture data yet. A named priority lead (a 2025 national fatal-dog-attacks registry) is identified but not extracted.

## Countries to Research in Phase 2
> **Superseded Session 11** — Canada and France have both been upgraded into "Countries Confirmed In Scope" above (they had real data since Session 6, just not reflected in this list until this session's reconciliation pass). Only Italy remains a genuine, never-yet-researched candidate from this original Phase 2 list.
- ~~Italy~~ **OPENED Session 11 (same continuation) -- no longer unresearched.** A new data/by-country/Italy.md file now exists with a genuine (though regional-only) bite-hospitalisation dataset -- see Table 1 above and its own file for full detail, including a named priority lead (a 2025 national fatal-dog-attacks registry paper, identified but not yet extracted) and remaining gaps (shelter/surrender, behavioural-problem prevalence, management-culture/legislative history all still unresearched for Italy).

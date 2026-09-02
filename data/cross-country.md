# Cross-Country Comparison Tables
> Phase 3 compilation. Updated after Phase 1 research.
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

---

## Table 4 — Composite Integration Score
> NOT YET POPULATED — requires Phase 5 analysis
> Pending: data normalisation, weighting methodology, gap-filling strategy

| Country | Bite Score | Surrender Score | Referral Score | Composite | Rank |
|---------|-----------|----------------|----------------|-----------|------|
| — | — | — | — | — | — |

---

## Countries Confirmed In Scope (data sufficient for inclusion)
- ✅ USA — strong data; bite and surrender metrics available
- ✅ UK (England) — strong data; bite and surrender metrics available
- ✅ Australia — strong data; bite and euthanasia metrics available; referral rate (partial)
- ⚠️ Netherlands — partial; bite data old (2010); shelter system incomparable
- ⚠️ Germany/Austria — variable and legislative data only; no bite/surrender statistics found yet
- ❌ Japan — data insufficient for quantitative comparison; qualitative only
- ❌ Scandinavia — fatality data only; insufficient for comparison
- ✅ New Zealand (added Session 11) — strong data; national ICD-10-AM hospitalisation rate, plus ethnicity/deprivation/regional gradients (Duncan-Sutherland et al. 2022)

**Note (Session 11):** this list otherwise still reflects an early Phase 1/2 compilation pass -- Canada and France, for example, both have real bite/shelter data extracted by Session 6 (see their own by-country files and data-sources.md) but are not yet reflected here. A full Phase 5 rebuild of this whole file, cross-checking every country's by-country file against this summary, remains a standing to-do -- not attempted this session to keep scope contained to the two named Session 10 next-actions plus this NZ find.

## Countries to Research in Phase 2
- Canada (data signposted: Canadian Vet Journal, 28 fatalities 1990–2007; Toronto BSL data)
- France (Eurostat fatality data available; shelter data unknown)
- Italy (Eurostat data exists; cultural context interesting)

**Note (Session 11):** New Zealand's Phase-2 placeholder above has been superseded -- see "Countries Confirmed In Scope" list, which now includes it.

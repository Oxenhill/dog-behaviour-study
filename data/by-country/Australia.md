# Australia — Data File

## Dog Bite Incident Data

**Primary source: AIHW (Australian Institute of Health and Welfare) — A grade**

| Metric | Figure | Year | Source |
|--------|--------|------|--------|
| Hospital admissions (dog bites) | 11.3 per 100,000 | 2000–2003 avg | AIHW NISU Briefing, dog-related injuries |
| Hospital admissions (dog bites) | 17 per 100,000 | 2013/14 | AIHW Fact Sheet, INJCAT 186 |
| Hospital admissions (dog bites) | 36.1 per 100,000 | 2023/24 | AIHW, Injury in Australia: Contact with living things |
| Total hospitalisations (all pets, crude rate) | 18.9 per 10,000 | 2012/13 | AIHW |
| Total hospitalisations (all pets, crude rate) | 47.5 per 10,000 | 2021/22 | AIHW |
| Fatality rate | 0.004 per 100,000 | Current | NALZO citing published research |
| Comparative (US fatality rate) | 0.05–0.07 per 100,000 | — | Published comparison |

**Sudden shift flagged:**
- Rate more than doubled from 2013/14 (17/100,000) to 2023/24 (36.1/100,000)
- 10% spike in 2020/21 specifically linked to first COVID lockdowns (AIHW ABC News report, March 2024)
- Similar pandemic-era surge to UK and USA — consistent global pattern
- Likely causation: pandemic pet acquisition increase (40% of Australian households own dogs, one of world's highest rates), inexperienced owners, increased close-quarters living

**Definition used:** Hospital admissions (public sector) for ICD-10 code W54 (bitten or struck by dog), AIHW National Hospital Morbidity Database. Comparable to NHS HES coding.

**Notes:**
- Children 0–9: highest risk group for bites (689 cases, 17% in 2013/14)
- Elderly: most likely to be struck (not bitten), leading to falls and fractures
- Rural rates significantly higher than urban rates
- Dog bites = 53% of all pet-related hospitalisations (dogs and cats combined most of 'living things' injury category)

**Population scope note (bite data):** AIHW hospital admission data (ICD-10 W54) is not restricted by ownership status. This is a live consideration for Australia specifically — free-roaming dog populations are documented in some remote and Indigenous communities, so national hospitalisation figures cannot be assumed purely household-sourced. Tagged **[Scope: mixed/unclear]**.

## Shelter Surrender / Relinquishment Data

**Primary source: RSPCA Australia Annual Statistics — A grade**

| Metric | Figure | Year | Source |
|--------|--------|------|--------|
| Dogs euthanased by RSPCA Australia | 17.46% (2,768) of dogs received | 2024/25 | RSPCA Australia Animal Outcomes Report 2024-25 |
| Surrender reason: behaviour | 12.2% of all surrenders | 2018 | RSPCA South Australia annual review |
| Surrender reason: too many pets | 11.7% | 2018 | RSPCA SA |
| Surrender reason: unable to keep | 9.9% | 2018 | RSPCA SA |
| Behaviour-related euthanasia context | "Not able to treat through behavioural modification" cited | 2024/25 | RSPCA Australia Animal Outcomes 2024-25 |
| Dogs entering shelters annually | ~200,000 (est. 2012/13) | 2012/13 | Cited in Chua et al. 2017 |
| Sunshine Coast region: behaviour as primary surrender reason | 15% | Cited | Carter and Taylor, cited in PMC8532592 |

**Confounder note:** Economic pressures and housing are co-factors in Australian surrenders. RSPCA euthanasia data links specifically to behaviour modification failure but full breakdowns of surrender reasons nationally are not published in accessible form beyond RSPCA SA case study.

**Behaviour-related euthanasia:**
- The RSPCA Australia 2024-25 report directly links euthanasia to inability to treat behaviour issues through modification programs and safety risk — this is a quality metric for integration failure
- 17.46% of dogs euthanased overall — comparable to Canadian and US figures but exact behaviour-specific euthanasia rate not isolated in national data

**Population scope note (shelter data):** RSPCA Australia's overall intake/euthanasia figures (e.g. the 17.46% euthanasia rate) are **[Scope: mixed/unclear]** — RSPCA shelters take in owner surrenders, strays, and seized dogs together without a national published breakdown. The RSPCA SA 12.2% 'behaviour' surrender figure specifically describes the surrender subset and is **[Scope: household-only]**.

## Behaviour Referral / Professional Data
> **Session 8 cross-reference (CORRECTION to an earlier draft of this note):** the 11.0% referral rate below is NOT new this session -- it was already logged (PMC7918417) in an earlier session and is the SAME VetCompass Australia young-dog mortality study reached this session via its MDPI mirror (Craig et al., Animals 2021, 2076-2615/11/2/493). What IS genuinely new this session is the broader context around that same study: the 82.8%-no-documented-treatment figure, the 29.7%-of-deaths-linked-to-undesirable-behaviour headline, the road-traffic-accident/dog-attack cause breakdown, and breed/neuter risk factors -- none of which were previously extracted into this file. Full detail in variables/behavioural-problem-prevalence.md, which also carries the important caveat that this study's 29.7% figure is a share of DEATHS, not a prevalence-in-the-living-population rate, and should not be read alongside the other countries' prevalence percentages without that distinction.

**Source availability: MODERATE**
- In Australian primary care practices: attending vet referred behaviour cases to behaviourist or trainer in 11.0% of all undesirable behaviour (UB) cases; pharmacological therapy attempted in 5.9% — *Source: PMC7918417, mortality study in dogs ≤3 years, primary-care VetCompass Australia data*
- 40% of Australian households own dogs (one of world's highest rates) — same source
- The above referral rate (11%) is one of the only published figures for behaviour referral practice from any country in this study

**Population scope note (referral data):** **[Scope: household-only]** — PMC7918417 draws on VetCompass Australia primary-care practice data, i.e. client-owned dogs under regular veterinary care.

## Variables — Key Facts

| Variable | Detail | Source |
|----------|--------|--------|
| Dog population | ~6 million dogs (est.) | Industry figures |
| Household ownership | ~40% of households | RSPCA/AIHW |
| Dog trainer regulation | None nationally — voluntary bodies only (DELTA, PPSA, etc.) | — |
| Breed legislation | State-based; ACT, NSW, QLD, VIC and others have BSL | State legislation |
| E-collar legislation | Banned: ACT, NSW, QLD, SA, Tasmania, Victoria | IACP 2025 tracker |
| Microchipping | Mandatory nationally (state-by-state implementation) | — |
| Leash laws | State/local; most require on-leash in public | — |
| Dog density | High; ~6M dogs / 26M population | — |

## Data Gaps
- National breakdown of shelter surrender reasons by category not published aggregated (RSPCA data is state-by-state)
- Behaviour referral rate as % of dog population not available nationally
- Long-term trend data for shelter behaviour surrenders not available

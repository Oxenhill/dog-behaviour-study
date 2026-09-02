# Canada -- Data File
> Phase 2 gap-filling target (Session 2). One focused search pass completed per _PROJECT_STATE.md Session 2 Decisions. Status: thin but not empty -- retained as a qualitative/partial-quantitative entry, not dropped.

## Dog Bite Incident Data

**Source quality: mixed -- one strong historical government-program source (CHIRPP), one small single-city peer-reviewed study, one national BSL-effectiveness study identified but not accessible this session**

| Metric | Figure | Year | Source |
|--------|--------|------|--------|
| Non-fatal dog bite ED cases (10 pediatric + 4 general hospitals) | 13,921 cases | 1990-2003 (cumulative through Jan 2005) | CHIRPP (Canadian Hospitals Injury Reporting and Prevention Program) injury brief |
| ED admission rate among bite cases | 4.9% | 1990-2003 | CHIRPP |
| Dog bite mortality rate | 0.01 per 100,000 | 1980-2002 | CHIRPP |
| Dog bite hospitalisation rate | 1.57 per 100,000 | fiscal year 2002-03 | CHIRPP |
| Adult ED dog bites, 3 EDs, ~400,000 catchment (Halifax, NS region) | 475 cases (~1% of all ED visits) | Jan 2013-Jun 2015 | Canadian Journal of Emergency Medicine, peer-reviewed |
| Hospital admissions from that 475-case sample | 3 (0.6%) | Jan 2013-Jun 2015 | Same study |
| Most frequently implicated breed type in that sample | Pit-bull type, 27% of cases | 2013-2015 | Same study |

**Population scope note:** CHIRPP and the Halifax ED study both capture bites regardless of the biting dog's ownership status -- neither source restricts to owned/household dogs. Canada has a negligible free-roaming urban dog population but documented free-roaming dog populations exist in some remote and northern/Indigenous communities, so this is tagged **[Scope: mixed/unclear]**, consistent with the USA/Australia entries in the scope audit.

**Temporal-linkage flag:** the CHIRPP hospitalisation rate (1.57/100,000, 2002-03) pre-dates this study's 2014-2024 window by over a decade and CANNOT be directly compared to the UK (~22/100,000, 2023/24) or Australia (36.1/100,000, 2023/24) figures without a like-for-like modern Canadian hospitalisation rate, which was not located this session. This is stated as a gap, not bridged with an estimate.

**Session 6 update -- EXTRACTED via a secondary summary (dogsbite.org), primary PDF/PMC access still blocked:** Raghavan, Martens et al., "Effectiveness of breed-specific legislation in decreasing the incidence of dog-bite injury hospitalisations in people in the Canadian province of Manitoba" (PMID 22753529). Access to the primary text remains blocked across PubMed, PMC, Cureus, and SafetyLit (reCAPTCHA/403/robots.txt errors, tried across Sessions 2 and 6) -- the figures below come from dogsbite.org's summary of the study. **[quality: C for this specific extraction route -- dogsbite.org is a breed-legislation-advocacy organisation, not a neutral secondary source; the underlying study itself is A-grade peer-reviewed, but these particular figures should be treated as provisional and re-verified against the primary text or a neutral secondary source (e.g. ResearchGate/Academia.edu copies, also identified but not yet fetched) in a future session before being used in the final report without caveat.]**

| Metric | Figure | Period | Notes |
|--------|--------|--------|-------|
| Study design | Population-level pre/post and geographic comparison across 16 Manitoba jurisdictions with pit-bull-type bans, using generalised estimating equations | 1984-2006 (23 years) | -- |
| Provincial dog-bite-injury-hospitalisation (DBIH) rate | 3.47 per 100,000 person-years (pre-BSL) -> 2.84 (post-BSL) | 1984-2006 | -- |
| Change in hospitalisation incidence, ALL jurisdictions | -18.1% | Same period | -- |
| Change in hospitalisation incidence, BSL-adopting jurisdictions specifically | -21.5% | Same period | -- |
| Change, ages 0-20, all jurisdictions | -25.5% | Same period | -- |
| Change, ages 0-20, BSL-adopting jurisdictions | -27.4% | Same period | Largest effect size in the study -- BSL "appeared particularly protective for children under 20" per the summarised conclusion |
| Direct pre/post comparison (unadjusted) | **No statistically significant reduction found** | Same period | Important caveat -- the headline population-level percentage changes above come from the adjusted/comparative model, not a simple before/after test |
| Jurisdictional comparison example | Winnipeg (BSL) vs Brandon (no BSL) showed a meaningful difference favouring Winnipeg | Same period | Cited as the clearest single comparison in the study |

**Cross-reference and Phase 5 significance:** this is the second major peer-reviewed BSL-effectiveness time-series study in the dataset, alongside Denmark's PLOS ONE study (see variables/breed-legislation-timeline.md). The two studies point in **different directions** -- Denmark found no statistically significant bite-reduction effect once properly trend-corrected; Manitoba's authors report a suggestive population-level association (strongest in the under-20 age group) but explicitly note the simple pre/post test was NOT significant, and the positive framing rests on the adjusted geographic-comparison model. Both nuances must be preserved in Phase 5 -- neither should be flattened into a simple "BSL works" / "BSL doesn't work" headline. Full write-up cross-referenced into variables/breed-legislation-timeline.md.

## Shelter Surrender / Relinquishment Data

**Source: Humane Canada, 2021 Canadian Animal Shelter Statistics Report -- A grade (national industry body, annual survey)**

| Metric | Figure | Year | Source |
|--------|--------|------|--------|
| Total dog intake (92 responding shelters) | 20,974 | 2021 | Humane Canada 2021 report |
| Dog euthanasia rate | 10% (~2,097 dogs) | 2021 | Humane Canada 2021 report |
| Owner-relinquishment linked to inability to afford veterinary care | >15% of owner-relinquished animals; ~75% of responding shelters reported this factor | 2021 | Humane Canada 2021 report |

**Population scope note:** Humane Canada's report combines stray and owner-surrender intake without a dog-specific published breakdown of the two categories in the content retrieved this session -- **[Scope: mixed/unclear]**.

**Definition/data gap:** Humane Canada's national report does NOT isolate "behaviour" as a surrender-reason category the way the US (SAC/Kisley), UK (Dogs Trust), or Australia (RSPCA SA) sources do -- it foregrounds economic/veterinary-cost factors instead. This is a genuine cross-country definitional difference, not a research failure -- flagged explicitly per the study's definition-caveat rule.

## Behaviour Referral / Professional Data
**Gap -- not located this session.** No Canadian national or provincial published rate of veterinary/behaviourist referral for dogs was found in this focused pass.

## Variables -- Key Facts
See variables/population-density-and-ownership.md for dog population (7.7M in 2020 -> 7.9M in 2022, CAHI) and density (4/km2). Breeding regulation and BSL for Canada not yet researched -- flagged as a gap in variables/breeding-regulation-and-ethics.md and variables/breed-legislation-timeline.md respectively (both currently silent on Canada).

## Data Gaps (Session 6 status -- updated)
- No 2014-2024-window Canadian bite hospitalisation rate directly comparable to UK/Australia -- most recent hospitalisation-rate figure located is still from 2002-03.
- ~~Manitoba BSL-effectiveness study (Raghavan et al.) identified but not accessible~~ **RESOLVED Session 6** via secondary summary -- primary text access itself remains blocked (flagged for re-verification, see note above).
- National/provincial behaviour referral rate: not found.
- Dog-specific (vs combined cat+dog) shelter intake breakdown by stray/surrender: not found.
- Provincial/territorial BSL and breeder-regulation timelines outside Manitoba: not researched.
- Calgary's off-leash-zone model was researched in Session 4 (see variables/management-practices-and-culture.md) -- management-culture side of Canada is now reasonably well covered even though bite/shelter metrics remain thinner.

**Session 2 verdict on scope decision:** per the "one more focused pass, then decide" instruction, Canada remains too data-thin for the main quantitative cross-country comparison (no directly comparable modern hospitalisation rate; no behaviour-referral rate) but has enough (CHIRPP historical baseline, Humane Canada 2021 shelter data, one small peer-reviewed ED study) to be retained as a qualitative/contextual entry in the final report, consistent with the "don't force global coverage, don't silently drop" rule.

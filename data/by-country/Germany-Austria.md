# Germany & Austria — Data File

*Note: Covered together due to similar legislative frameworks and shared language. Separated where data differs.*

## Dog Bite Incident Data

**Source: Limited published data in English — see gaps below**

| Metric | Figure | Year | Source |
|--------|--------|------|--------|
| European fatalities (Germany not top-listed) | — | 1995–2016 | Sarenbo & Svensson 2021 Eurostat |
| European fatality rate | 0.009 per 100,000 average | 2016 | Sarenbo & Svensson 2021 |
| Polish mean annual bite incidence (comparable neighbour) | 13 per 100,000 | 1994–2018 | ResearchGate / Polish study |

**Data gap flagged:** Germany-specific bite hospitalisation statistics in English-language peer-reviewed literature not located in Phase 1 search. German sources (Destatis, Robert Koch Institut) would require direct access. This is a significant gap — Germany is a candidate country with strong regulatory framework.

**Session 7 update -- Germany, official open-data source IDENTIFIED (not yet extracted to raw counts):** the Berlin Senate Administration for Justice and Consumer Protection (Senatsverwaltung fuer Justiz und Verbraucherschutz) publishes an annual, official, open-data "Hundebiss-Statistik" (dog bite statistics) dataset covering **2016-2024**, as downloadable CSV files per year, on Berlin's official open-data portal -- **[quality: A, government primary source; population-scope: unclear -- see caveat below]**.
- Portal record: `daten.berlin.de/datensaetze/hundebiss-statistik-berlin-1559673` (also mirrored on the national GovData.de portal)
- Methodology (as stated by the publisher): counts dogs that became "conspicuous toward people or other dogs through jumping or biting" ("Anspringen oder Beissen"), compiled from reports submitted to district offices (Bezirksaemter), broken down by breed.
- **This is city-level (Berlin only), NOT a national German figure** -- comparable in scope to a single US city or Canadian province, not to the UK/Australia national hospitalisation rate. It also measures REPORTED incidents (any severity, including non-injurious jumping-up incidents), not hospital admissions -- so it sits at a LOWER, less severe rung of the severity ladder (methodology/data-dictionary.md) than UK/Australia W54 data, closer to the "self-report/any-severity" end.
- **Session 11 update -- EXTRACTED:** the 2024 CSV was successfully pulled directly (`berlin.de/.../2025-08-14-biss-statistik-2024.csv`). **[quality: A, government primary source]**

| Metric | Figure | Year |
|--------|--------|------|
| Total dog bite/aggression incidents recorded | 977 | 2024 |
| Severe human injuries | 77 | 2024 |
| Minor human injuries | 446 | 2024 |
| "Dangerous lunges" at people (no contact/injury) | 97 | 2024 |
| Dog-to-dog injury only (no human involved) | 357 | 2024 |

**Breed breakdown (2024):**
| Category | Incidents | Notes |
|----------|-----------|-------|
| Berlin Rasseliste "dangerous breeds" (Pit Bull Terrier, American Staffordshire Terrier, Bull Terrier) | 34 combined | The full legally-restricted category |
| Other/mixed "dangerous" designations | 15 | -- |
| German Shepherd | 47 | NOT on the dangerous-breed list |
| Rottweiler | 42 | NOT on the dangerous-breed list |
| Non-classified mixed breeds | 254 | Largest single category |
| 200+ other individual breeds/mixes | Remainder | -- |

**Significance -- directly relevant to the study's management-culture-over-breed-legislation thesis:** Berlin's entire legally-"dangerous"-listed breed category accounts for only ~3.5% of recorded incidents (34/977), while German Shepherds alone (47) and Rottweilers alone (42) -- neither breed restricted under Berlin's Rasseliste -- each individually exceed that total. This is a single-city, quantitative, breed-by-breed dataset consistent with three other pieces of evidence already in this study: France's bite-severity survey (no breed-specific risk factor, France.md), the Austrian 271-vet survey ranking breed lowest among rated aggression causes (see Session 10 addition below), and Denmark's BSL-repeal-adjacent null result (variables/management-practices-and-culture.md). **Caveat preserved: this remains city-level (Berlin only), not a national German rate**, and it measures reported incidents of any severity (including non-injurious lunges), not hospital admissions -- it sits at the lower, self-report end of the severity ladder (methodology/data-dictionary.md), not directly comparable rung-for-rung to the UK/Australia W54 hospitalisation data.

**Austria-specific -- Session 7 update, EXTRACTED:**

**Graz University Hospital pediatric dog-bite study** -- **[quality: A -- hospital clinical-record study, peer-reviewed-adjacent research centre output]**
| Metric | Figure | Period | Notes |
|--------|--------|--------|-------|
| Children (0-14) treated for dog-related incidents, Univ. Hospital Graz | 296 | 2014-2018 | Pediatric and Adolescent Surgery dept. |
| Of those, actual bite cases | 212 | 2014-2018 | Remainder were non-bite incidents (e.g. scratches, knock-downs) |
| Requiring inpatient/surgical admission | 9% | 2014-2018 | This is the closest Austria-specific figure to a "hospitalisation" rung on the severity ladder, though from a single hospital catchment, not a national rate |
| Superficial scratches/minor wounds | 59% | 2014-2018 | -- |
| Bites to the head region | 50% | 2014-2018 | -- |
| Average age of injured children | 6.48 years (SD 3.8) | 2014-2018 | -- |
| Approximate annual rate at this one hospital | ~60 children/year | Ongoing (as stated in the source) | Single-catchment, not extrapolated to a national rate |

**Historical Austrian national trend (Osterreichisches Statistisches Zentralamt / OKV) -- [quality: B -- cited via a secondary kennel-club-affiliated source, original primary publication not directly located]:**
| Metric | 1980/1990 | 2002/2003 | Change |
|--------|-----------|-----------|--------|
| Animal-related injuries (ALL animals, not dog-specific -- Austria has no dog-exclusive national count per this source) | 6,572 (1980) | 3,005 (2002) | -54% over 22 years |
| Austrian dog population | 465,000 (1990) | 640,000 (2002) | +38% |
| OKV-certified dog-training exam passes | 8,764 (1990) | 33,617 (2003) | +284% |

**Significance -- directly relevant to the study's core management-culture/education hypothesis:** this Austrian historical series shows animal-injury incidents falling by roughly half over the same period the dog population grew by nearly 40% and OKV-certified training-exam completions nearly quadrupled. The source itself (OKV, an interested kennel-club party) attributes the decline to rising owner responsibility and professional training uptake -- this is a plausible but NOT independently verified causal claim (correlation over one long historical window, single source, pre-dating this study's own 2014-2024 primary window by a decade or more). Flagged as a suggestive but low-confidence data point for Phase 5, and cross-referenced into variables/dog-trainer-regulation.md given its direct relevance to that variable. The "no dog-exclusive count, ~80% of animal injuries assumed to involve dogs" caveat from the source itself must be preserved -- this is NOT a clean dog-only bite statistic.

## Shelter / Relinquishment Data

**Data gap flagged:** Neither Germany nor Austria have published aggregate national shelter data in English-accessible sources during Phase 1. Germany has numerous Tierschutzvereine (animal welfare organisations) that collect data locally but national aggregation is not standard.

**Session 7 update -- Germany, national shelter-capacity data EXTRACTED (Deutscher Tierschutzbund, the national animal-welfare federation -- the closest German equivalent to RSPCA/Dogs Trust):** **[quality: A -- national federation's own member survey, stated methodology]**
| Metric | Figure | Year | Notes |
|--------|--------|------|-------|
| Survey method | "Trendumfrage" (trend survey) of 218 Tierschutzbund-affiliated shelters, run with Fressnapf (pet-retail sponsor) | May 2024 | -- |
| Shelters reporting "very high" occupancy | 69% | 2024 | -- |
| Of those, full or overcrowded | 49% | 2024 | -- |
| Shelters with remaining intake capacity | Only 18% | 2024 | -- |
| Shelters reporting increased intake since 2022 | 82% | 2024 | 2022 marks the end of German COVID work-from-home mandates -- consistent with the same post-pandemic-surrender pattern seen in the UK/Netherlands/France data elsewhere in this study |
| Shelters reporting more sick animals with longer stays | 74% | 2024 | -- |
| Cited surrender drivers | Owner inexperience (fehlende Sachkunde), dogs with behaviour problems from inexperienced ownership, owner overwhelm/time shortage, rising veterinary costs | 2024 | Note: "fehlende Sachkunde der Vorbesitzer" (previous owners' lack of expertise) is explicitly named -- directly relevant to the owner-competency/Sachkundenachweis variable already tracked in this file |

**Definitional/coverage gap:** this survey measures shelter CAPACITY/occupancy pressure and qualitative surrender drivers, not a hard national dog-intake COUNT (no "X dogs entered German shelters in 2024" figure was located) -- it is a genuine, national, primary-quality source, but not yet a like-for-like match to the Humane Canada/Dogs Trust/RSPCA-style intake-count format used elsewhere in this study. A hard national intake count remains a gap.

**Also identified, not extracted this session (secondary/lower-priority):** several non-authoritative aggregator articles (adoptiereintier.de, duunddastier.de, watson.de) citing a rough "~80,000 dogs enter German shelters annually, ~300,000 animals resident at any time" figure -- **[quality: C -- none of these are the publishing organisation itself; the figure could not be traced to Tierschutzbund's own published data this session]**. Logged as an unconfirmed indicative figure only, explicitly NOT to be used as if it were the Tierschutzbund's own confirmed number.

**Austria shelter data: national level still a complete gap; first REGIONAL data point found Session 11.** **[quality: C -- regional news source citing an Upper Austria animal welfare org; NOT a national figure]**

Source: `ooe.orf.at/stories/3369565` ("Mehr Hunde und Katzen im Sommer abgegeben"), reporting on Pfotenhilfe OO (Upper Austria / Oberosterreich animal welfare organisation), 2024.
| Metric | Figure | Period |
|--------|--------|--------|
| New dogs taken in | 40 | Since Jan 2024 |
| Adult cats taken in | ~100 | Since Jan 2024 |
| Baby/kitten cats taken in | 100+ | Since May 2024 |
| Daily surrender requests received | 3-5 | Current (2024) |
| Cited surrender drivers | Rising pet food/vet costs; animals purchased from "questionable/budget" breeders with resulting health issues; emotional or under-planned acquisition decisions | 2024 |

**Caveat -- must be preserved:** this is REGIONAL (Upper Austria / Pfotenhilfe OO specifically), not a national Austrian figure, and does NOT resolve the national-level gap (see Data Gaps below). It is notable primarily as the first Austrian shelter-side data point of any kind located after four sessions of attempts, and for the striking gap between low actual dog intake (40) and much higher daily surrender interest (3-5/day), which suggests filtering/waitlisting or that most requesters don't follow through -- worth a mention alongside the other post-pandemic/cost-of-living surrender findings elsewhere in this study (UK, Netherlands, France, Germany).

**Proxy indicator:** Germany plans stricter breeder controls limiting to 3 bitches with puppies at a time — indicates legislative awareness of welfare/relinquishment link.

**Population scope note:** No bite or shelter data has been extracted for Germany or Austria yet (both flagged as Phase 2 gaps below). When Destatis, Robert Koch Institut, or German/Austrian shelter federation data is located, it must be scope-checked and tagged **[household-only / mixed-unclear / includes-strays]** before use in cross-country comparison — do not assume household-only by default.

## Variables — Key Facts (Germany)

| Variable | Detail | Source |
|----------|--------|--------|
| Dog population | ~34 million (EU estimated) — Germany has one of EU's largest dog populations | FEDIAF |
| Dog registration | Mandatory (local citizens office) | German law |
| Dog tax (Hundesteuer) | Mandatory annual tax per dog; discourages impulse buying. National municipal revenue exceeded EUR400 million for the first time in 2021 (Deutscher Tierschutzbund, Session 7) -- NRW alone collected EUR104.6M in the first 9 months of 2022. Revenue is rising, which the source frames as a proxy for rising per-dog tax burden/dog population, not a behaviour metric itself | German law; Deutscher Tierschutzbund (Session 7) |
| Dog trainer regulation | Paragraph 11 permit for commercial trainers (no specific exam, no training hours standard) | German law; perPETual article |
| Owner competency: federal | None — state-level only | — |
| Owner competency: Lower Saxony | Sachkundenachweis mandatory for ALL first-time owners since 2013 | NHundG Lower Saxony Dog Act |
| Owner competency: NRW | Mandatory for dogs >20kg/40cm shoulder height | NRW dog legislation |
| Owner competency: other states | Varies; Berlin and Saxony: strict leash laws | State legislation |
| BSL | State-level; Category 1 dogs prohibited (Pit Bull, Tosa, Dogo Argentino, Fila Brasileiro) | Federal import restriction + state laws |
| E-collar legislation | Banned under animal welfare law nationally | German Tierschutzgesetz |
| Prong collars | Banned | German Tierschutzgesetz |
| Microchipping | Mandatory (German citizens office registration) | German law |

## Variables — Key Facts (Austria)

| Variable | Detail | Source |
|----------|--------|--------|
| Dog population | Not specified separately | — |
| Owner competency: Vienna | 4-hour Sachkundenachweis mandatory for new owners since July 2019; Hundeführschein for listed breeds since 2010 | Vienna dog law |
| Owner competency: national | Mandatory certification introducing July 1, 2026 | Austrian Animal Protection Act amendment (Tierschutzbund report, June 2026) |
| Breeding regulation | All breeding must be registered with veterinary authority; Qualzucht (torture breeding) banned | TSchG (Tierschutzgesetz) |
| E-collar legislation | Banned under animal welfare law | Austrian Tierschutzgesetz |
| Prong collars | Banned | Austrian Tierschutzgesetz |
| BSL | Listed breeds: Pitbull, Rottweiler, Dogo Argentino — restricted; varies by federal state | Austrian state laws |

**Key distinction from UK/US:**
Both Germany and Austria (and Switzerland) have banned e-collars and prong collars under animal welfare law. Austria is now the first country to introduce mandatory owner competency testing nationally (July 2026). Germany's Lower Saxony has had mandatory owner competency since 2013.

**Significance for study:** These are the countries with the most developed owner education requirements. However, the lack of published outcome data (bite rates, surrender rates) makes it impossible to currently quantify the effect of these policies. This is a major analytical limitation to flag in the discussion.

## Data Gaps (Session 7 status -- updated)
- ~~Germany-specific bite incidence/hospitalisation rate: NOT FOUND~~ **RESOLVED (city-level) Session 11** -- Berlin's official open-data bite dataset for 2024 extracted in full (977 total incidents, severity and breed breakdown -- see above). City-level (Berlin), not national -- a genuine national German rate remains a gap; the 2016-2023 years of the same CSV series are also available for a future session if a multi-year trend is wanted.
- ~~Germany national shelter intake/surrender data: NOT FOUND~~ **PARTIALLY RESOLVED Session 7** -- Deutscher Tierschutzbund's May 2024 national capacity survey (218 shelters) extracted, but it measures occupancy pressure and qualitative drivers, not a hard intake COUNT. A ~80,000/year figure exists in circulation but could not be traced to an authoritative source this session -- logged as unconfirmed, not usable without further verification.
- Austria-specific bite data: **PARTIALLY RESOLVED Session 7** via the Graz University Hospital pediatric study (2014-2018) -- single-hospital-catchment, not national.
- Austria-specific shelter/surrender data: **PARTIALLY RESOLVED Session 11** -- a regional (Upper Austria, Pfotenhilfe OO) data point extracted (40 dogs taken in since Jan 2024, 3-5 daily surrender requests). A genuine NATIONAL Austrian shelter/surrender figure remains a complete gap.
- **Session 10 addition (Core Metric 5, cross-referenced):** a 271-vet Austrian survey (Hermann 2023, Vetmeduni Vienna diploma thesis) gives a vet-reported view of behaviour-complaint frequency and, notably, ranks owner interaction/training/socialisation far above breed as a cause of aggression (4.75-4.80/5 vs 3.17/5) -- directly supportive of this study's management-culture thesis. Full detail in variables/behavioural-problem-prevalence.md. This is vet-CASELOAD data, not a dog-population prevalence rate, so it does not resolve the shelter/surrender gap above, but it does meaningfully add to Austria's otherwise thin behaviour-data picture (alongside the Graz pediatric bite study from Session 7 and the OKV training-uptake series in variables/dog-trainer-regulation.md).
- Germany: no national (as opposed to Berlin-city) bite rate of any kind located.
- Germany: no hard national shelter dog-intake count from an authoritative source (Tierschutzbund's own number, if one exists, was not located this session -- their public communications this session emphasised capacity/occupancy rather than intake totals).
- Robert Koch Institut and Destatis were NOT successfully searched/fetched directly this session -- German-language search surfaced the Berlin/Tierschutzbund/Graz sources above instead, which turned out to be more directly relevant and accessible. RKI/Destatis remain unexplored avenues for a future session if the Berlin CSV extraction and a Tierschutzbund national intake count are not enough on their own.
- Tasso e.V. (Germany's national pet-microchip registry) was not searched this session -- named in Session 2/5 as a target, still not attempted.

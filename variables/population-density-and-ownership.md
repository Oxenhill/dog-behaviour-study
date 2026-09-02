# Variable: Population Density & Dog Ownership Rate
> Temporal note: population density is a slow-changing structural variable (does not meaningfully shift year to year for these countries) and is logged as a single current point-in-time figure with a brief historical note. Dog ownership rate and dog population DO shift meaningfully within the study's 2014-2024 window (pandemic acquisition surge, post-pandemic decline) and are logged as dated timelines per the project's temporal-linkage methodology -- do not read a single "current" ownership figure against a metric data point from a different year without checking this timeline first.

---

## Population Density (structural -- single point + trend note)

| Country | Density (people/km2) | Data year | Source |
|---------|----------------------|-----------|--------|
| Netherlands | 547 | 2026 (UN-based estimate) | Worldometer / UN Population Division |
| Japan | 336 | 2026 | Worldometer / UN Population Division |
| UK | 289 | 2026 | Worldometer / UN Population Division |
| Germany | 240 | 2026 | Worldometer / UN Population Division |
| Denmark | 142 | 2026 | Worldometer / UN Population Division |
| France | 122 | 2026 | Worldometer / UN Population Division |
| Austria | 111 | 2026 | Worldometer / UN Population Division |
| Sweden | 26 | 2026 | Worldometer / UN Population Division |
| USA | 38 | 2026 | Worldometer / UN Population Division |
| Finland | 18 | 2026 | Worldometer / UN Population Division |
| New Zealand | 20 | 2026 | Worldometer / UN Population Division |
| Norway | 15 | 2026 | Worldometer / UN Population Division |
| Australia | 4 | 2026 | Worldometer / UN Population Division |
| Canada | 4 | 2026 | Worldometer / UN Population Division |

**Note:** These are current (2026) figures, not 2014 baselines. National population density changes very slowly (well under 5% over a decade) for every country in this study, so using the current figure as a proxy for the whole 2014-2024 study window is a reasonable simplification -- unlike law/policy variables, this one genuinely does not need year-by-year tracking. Flagged as **[quality: B -- aggregator derived from UN data; not independently cross-checked against each national statistics office]**.

**Interpretive flag for later analysis:** Density spans nearly two orders of magnitude across the study set (4/km2 in Australia/Canada vs 547/km2 in the Netherlands) yet the Netherlands has the *lowest* documented bite-severity profile of any country studied (Phase 1/2 finding) and Australia has one of the *highest* and fastest-rising hospitalisation rates. This directly contradicts a naive "more crowding leads to more conflict" hypothesis and should be treated as a genuine, reportable finding, not smoothed over -- density alone does not appear to predict outcome; it likely interacts with ownership rate, breed mix, and regulation.

---

## Dog Population & Household Ownership Rate -- Timeline

> Where two sources disagree for the same country (methodology differs -- national representative survey vs. pan-European industry estimate), BOTH are logged, not reconciled by picking one. This is a data integrity requirement, not an oversight.

### United States
| Year | Dog population | % households | Source |
|------|----------------|---------------|--------|
| 2023-2025 | 83-89.7 million | ~50% (~68 million households) | APPA National Pet Owners Survey |

*No pre-pandemic (2014) baseline located yet -- flagged as gap.*

### United Kingdom
| Year | Dog population | % households | Source |
|------|----------------|---------------|--------|
| 2019 | ~9 million | -- | PFMA / Dogs Trust (cited in UK.md, Key Sudden Shifts) |
| 2022 | ~13.5 million (peak, pandemic surge) | -- | PFMA / Dogs Trust estimate |
| 2022 (FEDIAF) | 12.7 million | 33% | FEDIAF Facts & Figures 2022 |
| 2024 (PDSA) | 10.6 million | 28% | PDSA PAW Report 2024 |

**Discrepancy flagged:** FEDIAF (12.7M/33%, 2022) and PDSA (10.6M/28%, 2024) disagree meaningfully even accounting for the two-year gap and the post-pandemic decline. FEDIAF's figure is a pan-European industry-data estimate; PDSA's is a nationally representative YouGov survey specific to the UK and is generally considered the higher-quality source for UK-specific figures -- but both are logged here rather than silently discarding FEDIAF. The genuine, well-evidenced trend (independent of which point estimate is used) is: sharp rise 2019 to 2021/22 (pandemic acquisition), partial decline 2022 to 2024.

### Australia
| Year | Dog population | % households | Source |
|------|----------------|---------------|--------|
| Current (est.) | ~6 million | ~40% | Industry figures / RSPCA / AIHW (cited in Australia.md) |

*One of the highest household ownership rates in the study set. No dated multi-year series located yet -- flagged as gap.*

### Netherlands
| Year | Dog population | % households | Source |
|------|----------------|---------------|--------|
| 2021 | 1.8 million | 18% (2022 FEDIAF) | Dibevo/NVG survey (2021 figure); FEDIAF Facts & Figures 2022 (18%, 1.83M) |
| 2025 | 1.7 million (-5.6% vs 2021) | -- | Dibevo/NVG-commissioned survey, cited in GlobalPETS analysis |

**Correction to prior session estimate:** Netherlands.md previously logged dog population as "~1 million (likely overstated 90% ownership claim)." FEDIAF and the Dibevo/NVG survey both independently converge on ~1.7-1.8 million -- this is a materially better-sourced figure and should supersede the earlier rough estimate. Updated in Netherlands.md variables table this session.

### Germany
| Year | Dog population | % households | Source |
|------|----------------|---------------|--------|
| 2022 (FEDIAF) | 10.6 million | 21% | FEDIAF Facts & Figures 2022 |
| 2023 | 10.5 million | 21% | ZZF/IVH (German Pet Trade & Industry Association / Industrial Association of Pet Care Producers), Skopos survey of 5,000 people |
| 2024 | 10.5 million (flat vs 2023) | 21% | ZZF/IVH, same methodology |

**Consistency note:** Unusually for this study, German figures from two independent source families (FEDIAF pan-European estimate vs. ZZF/IVH national industry survey) closely agree -- this is one of the more reliable ownership figures in the dataset.

### Austria
| Year | Dog population | % households | Source |
|------|----------------|---------------|--------|
| 2022 | ~0.837 million | 17% | FEDIAF Facts & Figures 2022 |

*No independent Austria-specific national survey located yet to cross-check the FEDIAF figure -- flagged as single-source.*

### Japan
| Year | Dog population | Source |
|------|----------------|--------|
| 2015 | 7.99 million | Japan Pet Food Association, National Survey on Dog and Cat Ownership |
| 2024 | 6.796 million (-15% vs 2015) | Japan Pet Food Association |
| 2025 | 6.82 million (early recovery signal) | Japan Pet Food Association |

**Temporal-linkage significance:** Japan's only bite-incidence data point in this study (4,208 serious incidents, 2015) sits at the very start of a decade-long *decline* in the dog population (-15% by 2024). Any later attempt to estimate a 2024-equivalent bite rate from the 2015 figure must account for a materially smaller dog population, not just an unchanged one. No 2024-equivalent bite data exists to make this comparison directly -- stated as a compounding gap, not filled.

### Scandinavia (Sweden / Norway / Finland / Denmark)
| Country | Year | Dog population | % households | Source |
|---------|------|----------------|---------------|--------|
| Sweden | 2022 | 1.051 million | 15% | FEDIAF Facts & Figures 2022 |
| Norway | 2022 | 0.5 million | 17% | FEDIAF Facts & Figures 2022 |
| Finland | 2022 | 0.797 million | 24% | FEDIAF Facts & Figures 2022 |
| Denmark | 2022 | 0.643 million | 21% | FEDIAF Facts & Figures 2022 |

*Single-source (FEDIAF) for all four -- no independent national cross-check located yet.*

### Canada (candidate country -- Phase 2 gap-filling target)
| Year | Dog population | % households | Source |
|------|----------------|---------------|--------|
| 2020 | 7.7 million | -- | Canadian Animal Health Institute (CAHI) 2022 Pet Population Survey, Kynetec, n=4,000 |
| 2022 | 7.9 million | 60% (cats + dogs combined, not dog-only) | CAHI 2022 |

**Note:** The 60% figure is households owning "at least one cat or dog" -- not dog-specific. Dog-only household percentage not isolated in this source; flagged as a precision gap.

### New Zealand (candidate country -- Phase 2 gap-filling target)
| Year | Dog population | % households | Source |
|------|----------------|---------------|--------|
| 2020 | -- | 34% | Companion Animals NZ (CANZ), 2024 NZ Pet Data Report (retrospective figure) |
| 2024 | ~830,000 | 31% | CANZ 2024 NZ Pet Data Report, Insights HQ, fieldwork Sept-Oct 2024 |

**Trend:** Declining ownership rate 2020 to 2024 (34% to 31%), same direction as UK/Netherlands post-pandemic pattern.

### France (candidate country -- Phase 2 gap-filling target)
| Year | Dog population | % households | Source |
|------|----------------|---------------|--------|
| 2022 | 7.6 million | 20% | FEDIAF Facts & Figures 2022 |

*Single-source -- no French national statistics office (INSEE) cross-check located yet; this is one of the Phase 2 France research targets.*

---

## Data Gaps
- No 2014-baseline (pre-study-window start) dog population figure located for USA, Australia.
- Austria, Sweden, Norway, Finland, Denmark, France ownership figures are FEDIAF-single-source -- no independent national statistics body cross-check yet.
- Canada dog-only household ownership % (isolated from cat ownership) not found.
- FEDIAF's own PDF states 2022 methodology changed from prior years and "should not be compared to previous years" -- this limits any FEDIAF-internal trend analysis; only the Dibevo/NVG (Netherlands), ZZF/IVH (Germany), PFMA/PDSA (UK), and CANZ (NZ) series are safe to read as genuine year-over-year trends.

## Sources Log (to be mirrored into data-sources.md)
- Worldometer / UN Population Division -- population density -- [quality: B]
- FEDIAF Facts & Figures 2022 (PDF, europeanpetfood.org) -- dog population & ownership %, 12 European countries -- [quality: A -- industry body, EU-wide standardised methodology, cited academically]
- PDSA PAW Report 2024 -- UK dog population/ownership -- [quality: A]
- ZZF/IVH (German Pet Trade & Industry Association / Industrial Association of Pet Care Producers), Skopos survey -- German dog population -- [quality: B]
- Dibevo/NVG (Dutch Pet Trade Association / Dutch Pet Association) survey, cited via GlobalPETS -- Netherlands dog population trend -- [quality: B -- trade-association-commissioned survey]
- Japan Pet Food Association, National Survey on Dog and Cat Ownership -- [quality: A -- long-running national industry survey, widely cited]
- Canadian Animal Health Institute (CAHI) 2022 Pet Population Survey, Kynetec -- [quality: B]
- Companion Animals New Zealand (CANZ), 2024 NZ Pet Data Report, Insights HQ -- [quality: B]
- APPA National Pet Owners Survey -- USA -- [quality: B -- industry association survey, long-standing and widely cited]

**Population scope note:** All ownership/population figures above are, by survey construction, describing owned/household dogs (respondents are asked whether their household owns a dog) -- **[Scope: household-only]** for every entry in this file.

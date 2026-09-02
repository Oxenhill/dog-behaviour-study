# France -- Data File
> Phase 2 gap-filling target (Session 2). Research pass constrained by a WebFetch tool-usage limit hit mid-session (resets ~18:20 UTC) -- strong candidate primary sources were located via search but NOT extracted. Logged as identified-not-extracted per the data integrity rule; no figures below are estimated or invented.

## Dog Bite Incident Data

**Already established (prior session, carried over):**
| Metric | Figure | Year | Source |
|--------|--------|------|--------|
| Fatalities (cumulative) | 79 | 1995-2016 | Sarenbo & Svensson 2021, Forensic Science International (Eurostat ICD-10 W54) -- France is the 3rd-highest of the 13 European countries in that dataset, behind Hungary (94) and just ahead of the UK (56) |

**Session 6 update -- InVS/Sante publique France bite-severity survey, EXTRACTED (via secondary summary; primary PDF robots-blocked):**

The primary source (`recomedicales.fr/print/invs-morsure-chien.pdf`) is disallowed by that site's robots.txt and could not be fetched. The official Sante publique France landing page for the study (santepubliquefrance.fr) confirms the study's existence, period, and design but does not itself publish the statistical results. The figures below come from santevet.com (a veterinary-media outlet), a secondary summary of the same InVS survey -- **[quality: B -- secondary media summary of a government-run ED-surveillance study, not the primary document itself; figures not independently cross-checked against the primary PDF]**. Treat as provisional pending primary-source confirmation in a future session.

| Metric | Figure | Year / period | Source |
|--------|--------|----------------|--------|
| Estimated annual dog bites, France | ~250,000/year | study period 2009-2010 estimate | InVS multicentre ED survey, via santevet.com summary |
| Bite fatalities (cumulative) | 33 deaths | 20-year period preceding the study | Same |
| Fatalities among children under 15 | ~2/3 of all deaths | Same period | Same |
| Fatalities among children under 5 | 16 deaths | Same period | Same |
| Victims reporting lasting consequences (mostly scarring) | ~40% | 2009-2010 survey | Same |
| Bites occurring in the victim's own home/residential setting | ~68% | 2009-2010 survey | Same |
| Bites where the dog was known to the victim (family/neighbour/acquaintance) | Majority | 2009-2010 survey | Same |
| Bites perceived by the victim as unpredictable | ~74% | 2009-2010 survey | Same |
| Biting dogs with no documented history of prior bites | ~69% | 2009-2010 survey | Same |
| Breed-specific risk finding | **No evidence found linking specific breeds to higher bite frequency or severity** -- risk factors identified instead relate to dog's education/training, health status, and situational context | 2009-2010 survey | Same |

**Study design note (confirmed via santepubliquefrance.fr):** the InVS/Sante publique France programme ran in two phases -- an initial multicentre ED severity-factors survey (May 2009-June 2010, 8 hospitals) and a follow-up sequelae survey of the same bite victims 12+ months later (Sept 2010-Nov 2011). This gives France a genuine, purpose-built bite-severity dataset, structurally comparable in intent (though not in coding system) to the UK/Australia W54 hospital-admissions approach -- it is ED-survey-based rather than ICD-10-coded administrative data, so it sits at a different rung of the severity ladder (see methodology/data-dictionary.md) and should not be treated as numerically comparable to the UK/Australia hospitalisation rate without caveat.

**The breed-neutral finding is flagged as directly relevant to Phase 5 analysis** -- it is a French peer-reviewed-adjacent government finding that, like Denmark's PLOS ONE BSL null result, complicates a simple breed-legislation-effectiveness narrative, though via a different data type (bite-cause survey vs. law-change time series).

**Still NOT extracted (secondary/lower priority, not attempted this session):**
| Source | Apparent origin | Status |
|--------|------------------|--------|
| "Facteurs de gravité des morsures de chien aux urgences" (PDF, hosted at recomedicales.fr, filename `invs-morsure-chien.pdf`) | Filename strongly suggests INVS (Institut de Veille Sanitaire, the French national public health surveillance institute -- predecessor to Santé publique France) -- i.e. a genuine A-grade government ED-surveillance study of dog bite severity | Identified, NOT extracted. **Top priority for next session** -- this filename pattern is the closest thing to an NHS-HES/AIHW equivalent found for France so far |
| Afis Science (Association francaise pour l'information scientifique) article, "Risque de morsure de chien, ou le retour de la science" | Science-communication association, likely summarising the same or related INVS/academic data | Identified, NOT extracted -- secondary but potentially useful for locating the primary study it cites |
| France Nature Environnement, "Les morsures de chiens" | Environmental NGO article | Identified, NOT extracted, likely secondary/lower quality -- lower priority |

## Shelter Surrender / Relinquishment Data

**Session 6 update -- SPA national abandonment study, EXTRACTED (`SPA_Abandon_Etude_FR_Web.pdf`, la-spa.fr) -- [quality: A -- national animal-welfare authority's own study, 809 responding associations, published methodology]:**

| Metric | Figure | Year | Notes |
|--------|--------|------|-------|
| Dogs as share of animals taken in by surveyed shelters | 23% (cats 77%) | 2024 | Exact national dog-specific total not given -- survey covers a sample of associations, not a national census |
| Minimum animals sheltered by surveyed associations | 108,000+ | 2024 | Stated as a floor, not a national total -- actual national figure "likely several times higher" per the source |
| Intake requests refused due to saturated capacity | 38,000+/year | 2024 | -- |
| Average dogs on waiting lists per association | 17 | as of 31 Dec 2024 | -- |
| Dogs arriving via direct owner abandonment | 59% | 2024 | vs 28% found as strays, 8% seized by authorities, 5% other |
| Top reason for direct abandonment | Life disruption (divorce, job loss, relocation) -- 28% | 2024 | Followed by: owner incapacity (illness/death/care home) 24%; unwanted litters 18%; allergies 9%; financial hardship 7% |
| Purebred vs mixed-breed dogs surrendered | 34% purebred (11% legally-restricted "category" breeds) / 66% mixed | 2024 | -- |
| Dogs arriving with injuries/health conditions | 30-40% | 2024 | -- |
| Average shelter stay | 8 months | 2024 | -- |
| Adoption success rate (not returned) | 98% | 2024 | -- |
| Annual adoption rate of dogs taken in | 80% | 2024 | -- |
| Seasonal pattern | None strong for dogs (stable year-round, minor July/October upticks) -- contrasts with a stronger seasonal pattern for cats | 2024 | -- |
| Associations reporting concern for their own organisational viability | 86% (74% cite financial strain specifically) | 2024 | Structural/capacity context, not a behaviour metric, but relevant to household-integration "success" framing -- shelter capacity itself may be a bottleneck independent of dog behaviour |

**Population scope note:** this is shelter/association intake data (owned dogs abandoned + strays taken in) -- **[Scope: mixed/unclear]**, since 28% of intakes are stray/found dogs, consistent with the shelter-data scope pattern seen in Canada (Humane Canada) and the UK (Dogs Trust).

**Not yet located/extracted:** the Assemblee Nationale parliamentary question (QANR5L16QE17058) referenced in Session 2 search results was not re-attempted this session -- remains a lower-priority government cross-check target.

## Behaviour Referral / Professional Data
**Gap -- not located this session.**

## Variables -- Key Facts (from population-density-and-ownership.md and breeding-regulation-and-ethics.md, cross-referenced)
| Variable | Detail | Source |
|----------|--------|--------|
| Population density | 122/km2 | Worldometer/UN, 2026 |
| Dog population | 7.6 million (2022) | FEDIAF Facts & Figures 2022 |
| Household ownership | 20% (2022) | FEDIAF Facts & Figures 2022 |
| EU-wide breeder registration/traceability rules | Applies to France as an EU member -- see variables/breeding-regulation-and-ethics.md (COM(2023) 769, and the unconfirmed April 2026 EU Parliament rules) | -- |

France-specific breeding regulation and BSL history not yet researched -- flagged as gaps.

## Data Gaps (Session 6 status -- updated)
- ~~INVS/Sante publique France dog-bite-severity ED study -- identified, not extracted~~ **RESOLVED Session 6** via secondary summary (santevet.com); primary PDF remains robots-blocked, figures are provisional pending primary confirmation.
- ~~SPA national abandonment study -- identified, not extracted~~ **RESOLVED Session 6** -- full national shelter/abandonment dataset now logged above.
- No French national bite HOSPITALISATION rate directly comparable to UK/Australia W54 coding located or confirmed -- the InVS figures are ED-survey-based, not ICD-10 hospital-admission-coded, so this specific comparability gap remains even after Session 6's extraction.
- No French behaviour-referral data located.
- France-specific breeding regulation and BSL history not researched -- still a gap (management-culture/leash-law side, by contrast, WAS researched in Session 4 -- see variables/management-practices-and-culture.md).
- Assemblee Nationale parliamentary question on abandonment stats -- identified (Session 2), not re-attempted.

**Session 6 verdict:** France has moved from "identified-not-extracted" to a genuinely well-populated country file for bite-severity and shelter data, plus its existing leash-law/management-culture content from Session 4. Remaining named gaps are narrower and more specific (hospitalisation-rate comparability, breed-legislation history) rather than whole-category absences.

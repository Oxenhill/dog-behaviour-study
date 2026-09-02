# New Zealand -- Data File
> Phase 2 gap-filling target (Session 2). Research pass partially completed -- a WebFetch tool-usage limit was hit mid-session (resets ~18:20 UTC) before full-text extraction of the two most important NZ studies could be completed. Sources are identified and logged below; specific figures from them are marked NOT YET EXTRACTED rather than estimated or invented, per the project's data integrity rule.

## Dog Bite Incident Data

**Sources identified this session (titles/indexing confirmed via PubMed search; full-text NOT extracted due to a WebFetch session limit hit mid-pass):**

| Source | Citation | Status |
|--------|----------|--------|
| Mair et al. 2019 | "The incidence and risk factors of dog bite injuries requiring hospitalisation in New Zealand," NZMJ 132(1494):8-14 | Identified in prior session (data-sources.md) and re-confirmed via PubMed this session (PMID 31048820). **Full abstract/findings NOT extracted this session** -- flagged for immediate follow-up next session, this is the single named Phase 2 target from _PROJECT_STATE.md and remains incomplete |
| Follow-up/updated study, 2022 | "Epidemiology of dog-related injuries within New Zealand," NZMJ vol 135 no 1554 (PDF directly located at nzmj.org.nz) | Newly identified this session -- appears to be a more recent update to the Mair et al. dataset. **Not extracted** -- same tool-limit block |
| Related, 2022 | "An audit of dog-related injury notification practices in a New Zealand public hospital" (PMID 35728209) | Newly identified this session. **Not extracted.** |

**Session 6 update:** re-attempted the Mair et al. 2019 PubMed abstract once this session (per the project's one-attempt-per-session efficiency rule) -- pubmed.ncbi.nlm.nih.gov returned a reCAPTCHA interstitial, same failure mode as before. NOT a WebFetch budget issue this time (budget was available) -- this specific PubMed URL appears to be consistently bot-blocked regardless of session state.

**Session 11 update -- MAJOR RESOLUTION.** The 2022 follow-up study's direct nzmj.org.nz PDF was fetched successfully this session. **[quality: A -- national administrative data, ACC claims + National Minimum Dataset hospital discharges, ICD-10-AM external cause codes]**

**Duncan-Sutherland et al. 2022, "Epidemiology of dog-related injuries within New Zealand," NZMJ vol 135 no 1554:**
| Metric | Figure | Period |
|--------|--------|--------|
| Total ACC claims, dog-related injuries (DRIs) | 108,324 | Jul 2014-Jun 2019 (5 yrs) |
| Of those, dog bites specifically | 54,754 (51%) | Same period |
| Total DRI hospitalisations | 3,456 | Same period |
| Of those, dog bite hospitalisations | 3,084 (89%) | Same period |
| All-DRI incidence rate | 479.7 per 100,000/yr (average) | Same period |
| Dog bite incidence rate | 242.5 per 100,000/yr (average) | Same period |
| **DRI hospitalisation rate** | **15.3 per 100,000/yr (average)** | Same period |
| **Dog bite hospitalisation rate** | **13.7 per 100,000/yr (average)** | Same period |

**This is a genuine severity-ladder rung match to the UK/Australia hospitalisation data (methodology/data-dictionary.md)** -- it uses ICD-10-AM external cause codes on a national hospital-discharge dataset (National Minimum Dataset), the same broad approach as the UK/Australia W54 figures already logged elsewhere in this study, making New Zealand the third country in this study (after UK and Australia) with a genuinely comparable national bite-hospitalisation rate. Cross-reference this figure directly against the UK/Australia rates when the cross-country comparison table is built in Phase 5.

**Temporal trend:** hospitalisations for all DRIs rose 2.43%/year over the study window, and the paper places this in a near-eightfold long-run increase (1.7 per 100,000 in 1979 to 13.4 in 2018/19) -- a rising-incidence finding that should be checked against the UK/Australia trend direction already logged elsewhere.

**Demographic gradients (all new, high-value findings for this study):**
| Gradient | Finding |
|----------|---------|
| Age | Children 0-9: hospitalisation rate 22.0/100,000 (highest of any age group); 54% of their injuries to head/neck. Adults: dog bite hospitalisation rate 13.5/100,000, 87% of injuries to limbs/torso. |
| Ethnicity (Maori vs non-Maori) | Maori children 0-9 2.47x more likely to be hospitalised for a dog bite than non-Maori; Maori adults 2.50x more likely; Maori dog-bite hospitalisation rate 29.1/100,000 vs non-Maori 10.8/100,000 |
| Socioeconomic deprivation | ACC claims 3.38x higher in the most-deprived decile (10) vs least-deprived (1); hospitalisations 3.97x higher |
| Regional | Highest: Opotiki (695.7/100,000), Kawerau (641), Far North (497.7). Lowest: Wellington City (116.0), Palmerston North (104.6) |
| Severity | 72% of hospitalised bite victims required 2+ procedures; average hospital stay 2.3 days |

**Significance for this study:** the ethnicity and deprivation gradients are a genuinely new analytical dimension not yet present elsewhere in this study's bite data -- worth flagging for the Phase 5 discussion as a candidate explanatory variable (socioeconomic access to secure fencing/containment, dog-management resources, or veterinary/training access) alongside the management-culture variables already tracked. This should be cross-referenced into a future urban-vs-rural.md or veterinary-access.md variable file once those are started (both still unstarted as of Session 10/11).

**Population scope:** the paper does not restrict to household/pet dogs specifically -- it captures all dog-related injury claims/hospitalisations regardless of the dog's ownership status. **[Scope: mixed/unclear]** -- flag accordingly in any cross-country household-only comparison.

**Data source note:** the underlying Mair et al. 2019 paper (NZMJ 132(1494):8-14, PMID 31048820) remains itself unextracted -- it appears to be an earlier/shorter-window analysis of a similar ACC/NMDS dataset, now superseded in richness by the Duncan-Sutherland 2022 paper extracted above. Given the 2022 paper's much greater detail and more recent window, further attempts to extract Mair et al. 2019 specifically are now LOW PRIORITY -- the 2022 paper covers the same underlying data sources with more analytical depth.

**Management-culture side (leash law) RESOLVED this session -- see variables/management-practices-and-culture.md for full write-up:** the Dog Control Act 1996 s54A requires owners to have their dog on a leash OR carry a leash in public (not necessarily leash-on at all times), with a working-dog exemption. The specific designation of on-leash vs off-leash areas is delegated to individual territorial councils' bylaws (structurally the same "national floor + local council-designated zones" pattern seen in Australia and Canada), rather than being fixed in the national Act itself. Primary legislation.govt.nz and nzlii.org text both returned 403 errors when fetched directly (one attempt each, both blocked) -- this finding is sourced from communitylaw.org.nz, a legal-aid community-law reference guide, **[quality: B -- secondary legal-reference summary, not the primary statutory text]**.

## Shelter Surrender / Relinquishment Data

**Sources identified this session:**
| Source | Citation | Status |
|--------|----------|--------|
| SPCA New Zealand Annual Reports | 2018-19 and 2019-20 editions located (spca.nz, direct PDF URLs captured) | Identified, not yet extracted |
| Post-Adoption Problem Behaviours study | "Post-Adoption Problem Behaviours in Adolescent and Adult Dogs Rehomed through a New Zealand Animal Shelter," Animals (MDPI), doi:10.3390/ani8060093 | **EXTRACTED Session 9** -- a Session 2 top-priority target, finally pulled this session. 61 dogs tracked 1 week-6 months post-adoption (Auckland shelter, Nov 2015-Jul 2016): 70% had at least one reported problem behaviour (poor manners 46%, destruction 30%, high energy 28%, fear of strangers 25%, aggression to people/dogs 19% each), but 87% of adopters were not concerned or only mildly concerned. Full table and analysis in variables/behavioural-problem-prevalence.md -- directly relevant to this study's household-integration-success question. |
| SPCA 2025 Dog Policy Recommendations | spca.nz PDF, addressed to Minister Hoggard | Identified -- likely contains SPCA's own framing of current dog-behaviour/welfare issues in NZ; not yet extracted |

## Behaviour Referral / Professional Data
**Gap -- not located this session.**

## Variables -- Key Facts (from population-density-and-ownership.md, cross-referenced)
| Variable | Detail | Source |
|----------|--------|--------|
| Population density | 20/km2 | Worldometer/UN, 2026 |
| Dog population | ~830,000 (2024) | Companion Animals NZ (CANZ) 2024 NZ Pet Data Report |
| Household ownership rate | 34% (2020) -> 31% (2024), declining | CANZ 2024 report, Insights HQ fieldwork Sept-Oct 2024 |

Breeding regulation and BSL for New Zealand not yet researched this session -- flagged as gaps in variables/breeding-regulation-and-ethics.md and variables/breed-legislation-timeline.md.

## Data Gaps (Session 9 status -- updated)
- ~~Mair et al. 2019 findings~~ -- **LOW PRIORITY as of Session 11** (superseded in analytical depth by the 2022 Duncan-Sutherland paper below; not worth further blocked-PubMed attempts).
- ~~2022 follow-up NZMJ study findings~~ **RESOLVED Session 11** -- see Dog Bite Incident Data above. This is now New Zealand's headline bite-hospitalisation figure and a genuine severity-ladder match to the UK/Australia data.
- SPCA annual reports (2018-19, 2019-20 editions) and the SPCA 2025 Dog Policy Recommendations PDF -- still identified, not extracted; this is now the last remaining NZ shelter-data gap after the post-adoption study was resolved below.
- NZ breeding regulation and BSL -- not researched.
- ~~Leash-law / management-culture~~ **RESOLVED Session 6** -- see variables/management-practices-and-culture.md.
- ~~Post-Adoption Problem Behaviours study~~ **RESOLVED Session 9** -- see updated Shelter Surrender section above and variables/behavioural-problem-prevalence.md. This closes out a target named as top-priority all the way back in Session 2.

**Session 2 verdict on scope decision:** New Zealand has multiple strong, directly relevant, government/peer-review-quality sources identified (NZMJ x2, SPCA x2-3, an MDPI post-adoption-behaviour study) -- this is NOT a data-availability problem like Japan or Scandinavia's shelter gap. This is purely a this-session extraction shortfall caused by a tool limit. Recommend treating New Zealand as high-priority (not "drop" or "footnote-only") for the very next research session, ahead of further Canada or France work, since the sources are already in hand.

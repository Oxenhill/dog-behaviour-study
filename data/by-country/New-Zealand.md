# New Zealand -- Data File
> Phase 2 gap-filling target (Session 2). Research pass partially completed -- a WebFetch tool-usage limit was hit mid-session (resets ~18:20 UTC) before full-text extraction of the two most important NZ studies could be completed. Sources are identified and logged below; specific figures from them are marked NOT YET EXTRACTED rather than estimated or invented, per the project's data integrity rule.

## Dog Bite Incident Data

**Sources identified this session (titles/indexing confirmed via PubMed search; full-text NOT extracted due to a WebFetch session limit hit mid-pass):**

| Source | Citation | Status |
|--------|----------|--------|
| Mair et al. 2019 | "The incidence and risk factors of dog bite injuries requiring hospitalisation in New Zealand," NZMJ 132(1494):8-14 | Identified in prior session (data-sources.md) and re-confirmed via PubMed this session (PMID 31048820). **Full abstract/findings NOT extracted this session** -- flagged for immediate follow-up next session, this is the single named Phase 2 target from _PROJECT_STATE.md and remains incomplete |
| Follow-up/updated study, 2022 | "Epidemiology of dog-related injuries within New Zealand," NZMJ vol 135 no 1554 (PDF directly located at nzmj.org.nz) | Newly identified this session -- appears to be a more recent update to the Mair et al. dataset. **Not extracted** -- same tool-limit block |
| Related, 2022 | "An audit of dog-related injury notification practices in a New Zealand public hospital" (PMID 35728209) | Newly identified this session. **Not extracted.** |

**Session 6 update:** re-attempted the Mair et al. 2019 PubMed abstract once this session (per the project's one-attempt-per-session efficiency rule) -- pubmed.ncbi.nlm.nih.gov returned a reCAPTCHA interstitial, same failure mode as before. NOT a WebFetch budget issue this time (budget was available) -- this specific PubMed URL appears to be consistently bot-blocked regardless of session state. **Recommendation for next session: stop retrying the PubMed URL itself; instead try the nzmj.org.nz vol-132-no-1494 issue PDF directly (confirmed to exist and list the article, but full PDF not yet fetched), or a ResearchGate/Academia.edu mirror if one exists.** The nzmj.org.nz vol-135-no-1554 (2022 follow-up) direct PDF URL captured in Session 2 was also not re-attempted this session -- remains a named target.

**Management-culture side (leash law) RESOLVED this session -- see variables/management-practices-and-culture.md for full write-up:** the Dog Control Act 1996 s54A requires owners to have their dog on a leash OR carry a leash in public (not necessarily leash-on at all times), with a working-dog exemption. The specific designation of on-leash vs off-leash areas is delegated to individual territorial councils' bylaws (structurally the same "national floor + local council-designated zones" pattern seen in Australia and Canada), rather than being fixed in the national Act itself. Primary legislation.govt.nz and nzlii.org text both returned 403 errors when fetched directly (one attempt each, both blocked) -- this finding is sourced from communitylaw.org.nz, a legal-aid community-law reference guide, **[quality: B -- secondary legal-reference summary, not the primary statutory text]**.

## Shelter Surrender / Relinquishment Data

**Sources identified this session:**
| Source | Citation | Status |
|--------|----------|--------|
| SPCA New Zealand Annual Reports | 2018-19 and 2019-20 editions located (spca.nz, direct PDF URLs captured) | Identified, not yet extracted |
| Post-Adoption Problem Behaviours study | "Post-Adoption Problem Behaviours in Adolescent and Adult Dogs Rehomed through a New Zealand Animal Shelter," Animals (MDPI), doi:10.3390/ani8060093 | Identified -- this is directly relevant to the study's household-integration-success question (post-adoption behaviour outcomes specifically), not just intake reasons. Not yet extracted. |
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

## Data Gaps (Session 6 status -- updated)
- Mair et al. 2019 findings -- STILL NOT EXTRACTED after a second blocked attempt (Session 6); recommend switching approach (nzmj.org.nz direct PDF or a mirror) rather than retrying PubMed again.
- 2022 follow-up NZMJ study findings -- not extracted, not re-attempted this session.
- SPCA shelter intake/surrender numbers and behaviour-reason breakdown -- not extracted, not attempted this session.
- NZ breeding regulation and BSL -- not researched.
- ~~Leash-law / management-culture~~ **RESOLVED Session 6** -- see variables/management-practices-and-culture.md.

**Session 2 verdict on scope decision:** New Zealand has multiple strong, directly relevant, government/peer-review-quality sources identified (NZMJ x2, SPCA x2-3, an MDPI post-adoption-behaviour study) -- this is NOT a data-availability problem like Japan or Scandinavia's shelter gap. This is purely a this-session extraction shortfall caused by a tool limit. Recommend treating New Zealand as high-priority (not "drop" or "footnote-only") for the very next research session, ahead of further Canada or France work, since the sources are already in hand.

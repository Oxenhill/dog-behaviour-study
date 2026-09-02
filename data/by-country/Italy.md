# Italy -- Data File
> NEW country, Session 11 (autonomous continuation). Previously listed only as a "Countries to Research in Phase 2" placeholder (data/cross-country.md) with no dedicated file. Opened this session after the C-BARQ published-articles-list check surfaced Italy's existing pet-insurance-penetration figure (variables/veterinary-access.md, 29%) with no bite/surrender/prevalence data behind it -- a targeted search found genuine, extractable Italian sources.

## Dog Bite Incident Data

**Source: Alberghina, Virga, Sottile, Buffa & Panzera (2023), "A 10-year retrospective analysis (2012-2021) of hospitalizations resulting from dog bites in Southern Italy," Frontiers in Veterinary Science -- [quality: A, peer-reviewed, regional administrative hospitalisation data] -- [Scope: mixed/unclear -- hospitalisation data does not distinguish owned/stray dogs as the biting animal]**

Regional study covering Sicily, Italy's largest administrative region, 2012-2021, n=449 dog-bite injury hospitalisation (DBIH) cases.

| Metric | Figure | Period |
|--------|--------|--------|
| Total cases analysed | 449 | 2012-2021 |
| DBIH incidence rate, start of period | 0.648 per 100,000 (95% CI 0.565-0.731) | 2012 |
| DBIH incidence rate, end of period | 1.162 per 100,000 (95% CI 1.078-1.247) | 2021 |
| Trend | Statistically significant increase (P<0.01), both male and female victims | 2012-2021 |
| Highest-risk age group | Preschoolers (0-5 years): 59 cases, incidence 2.233 per 100,000 (95% CI 1.730-2.882) | Same period |
| Notable secondary finding | School-age children (6-12) showed similar risk to preschoolers; risk declined for other age groups; DBIH duration (hospital days) increased significantly with age | Same period |

**This is a genuine severity-ladder rung match (methodology/data-dictionary.md)** to the UK/Australia/New Zealand hospitalisation-based figures -- but it is REGIONAL (Sicily only, not a national Italian rate) and its absolute values (0.648-1.162 per 100,000) are an order of magnitude LOWER than the UK (~22), Australia (36.1), and New Zealand (13.7) national figures. This gap is large enough that it likely reflects a genuinely different DBIH definition/coding threshold in the source Italian hospital-discharge data (SDO, Scheda di Dimissione Ospedaliera) rather than a true tenfold-lower bite-hospitalisation reality -- this study's methodology section was not extracted in enough depth this session to confirm the exact coding threshold used, and this comparison should be treated as indicative only, not a like-for-like ranking, until that is checked. Flagged as a specific item for a future session rather than asserted as a real cross-country difference.

**Population context (from the same source's introduction):** Italy's owned dog population was reported as ~8.3 million in 2020, an increase of ~18% over the prior year -- Italy's dog population grew steadily 2014-2020 after a stable period, per the source's own citation (not independently re-verified this session).

**RESOLVED, same session (later continuation) -- a PMC mirror was found and extracted via direct device-side curl after MDPI's own site returned a 403.**

**Source: "Fatal Dog Attacks in Italy (2009-2025): The Urgent Need for a National Risk Registry," MDPI Animals 15(24):3523 (2025), via PMC12729952 -- [quality: A, peer-reviewed] -- [Scope: household-only for 92.6% of cases -- see below, a genuinely strong scope match for this study]**

A genuinely NATIONAL Italian dataset (unlike the Sicily-only hospitalisation study above), built from cross-verified national/regional media reporting (not administrative hospital records) over a 17-year period.

| Metric | Figure | Period |
|--------|--------|--------|
| Total fatal dog attacks recorded | 54 | 2009-2025 |
| Annual incidence range | 1-5 cases/year, peaks in 2012, 2024, 2025 (5 deaths each); minimum 2014 (1 death) | Same period |
| Statistical trend (Poisson regression) | NOT statistically significant (IRR 1.03, 95% CI 0.98-1.08, p=0.24) -- "relative temporal stability" despite visible peaks | Same period |
| Most-affected victim groups | Elderly (>=65) and preschool-aged children (<=4) | Same period |
| Breed involvement | Molosser and bull-type breeds implicated in 69% of cases | Same period |
| Dog ownership status | 92.6% of attacks involved OWNED dogs -- more than half belonging to the victim's own household | Same period |
| Attack setting | 66.7% occurred in private settings (victim's home/garden) | Same period |
| Two-era regulatory comparison (the study's own framing) | 1984-2009 (breed-specific legislation era): 1.28 fatalities/year average. 2009-2025 (owner-accountability/behavioural-assessment era, after Italy's national BSL repeal): 3.18 fatalities/year average | Both eras compared directly by the source |

**This is a significant, genuinely complicating data point for this study's management-culture-over-breed-legislation thesis, and it must be logged honestly rather than smoothed into the existing pattern.** Two things pull in different directions within this single source: (1) breed involvement in FATAL attacks specifically is high (69% molosser/bull-type) -- a different picture from the breed-neutral findings this study has assembled for bite SEVERITY/frequency more broadly (France, Austria, Berlin, Canada, Sweden, the Nordic qualitative study); (2) the raw fatality RATE nonetheless rose after Italy moved FROM breed-specific legislation TO an owner-accountability model (1.28/yr -> 3.18/yr), which -- taken at face value -- would cut AGAINST this study's accumulated evidence that management-culture/owner-behaviour factors matter more than breed-focused legislation. **Critical confounders the source itself names and this study must carry forward:** Italy's owned-dog population reportedly more than doubled over the past decade (per the source's own citation of Italy's National Canine Registry, not independently verified this session) -- a rising raw fatality count alongside a rising dog population is NOT the same as a rising per-capita risk, and this study should not treat the 1.28->3.18/yr figures as a controlled before/after comparison without that population-growth context. This is exactly the kind of nuance this study's temporal-linkage methodology (methodology/data-dictionary.md) exists to surface rather than paper over -- flagged prominently here and cross-referenced into variables/breed-legislation-timeline.md rather than being left to sit quietly in a country file where it might not inform the final report's discussion of breed-legislation effectiveness.

**Also worth noting for scope-tagging purposes:** at 92.6% owned-dog involvement, this is one of the strongest household-scope matches of any bite/fatality dataset in this entire study -- most other countries' hospitalisation-based bite data cannot distinguish owned from stray dogs as the biting animal (see this file's population-scope note below), but this Italian fatality study explicitly reports ownership status.

**Also identified, not pursued (narrower/older, lower priority than the two above):**
- "Incidence of injuries caused by dogs and cats treated in emergency departments in a major Italian city" (ResearchGate) -- older, single-city ED study, city not confirmed this session.
- "Incidence and characteristics of hospitalizations after dog's bite injuries in Sicily (Italy) between 2012-2015" (PubMed) -- appears to be an EARLIER, shorter-window version of the same Sicily dataset extracted above (2012-2021 supersedes 2012-2015); not separately pursued as likely redundant.

## Shelter / Surrender Data

**Not resolved this session.** A search for Italian national shelter-surrender statistics with an isolated "behaviour" reason category found only "RandAgiamo, a Pilot Project Increasing Adoptability of Shelter Dogs in the Umbria Region" (Animals, MDPI, PMC4598705) -- this is a single-region (Umbria) ADOPTABILITY-improvement intervention study, not a national surrender-reason survey, and was not extracted as it does not answer this study's question. Italy's shelter/surrender data is a genuine, unresolved gap as of Session 11 -- no national source was located or ruled out beyond this one attempt, consistent with the project's efficiency rule (one attempt per session before moving on).

## Behavioural-Problem Prevalence (Core Metric 5)

**Not searched this session.** No C-BARQ or other owner-survey behaviour-prevalence source for Italy was sought this session -- opening this country file and extracting the bite-hospitalisation data above was this session's full scope for Italy given remaining time/context. A dedicated Core Metric 5 search for Italy is a clear next-session target -- note that the C-BARQ published-articles list (vetapps.vet.upenn.edu/cbarq/published-articles.cfm) did NOT surface any Italy-specific C-BARQ study during this session's check (Portugal, Sweden, Japan, Canada, France, Germany were surfaced; Italy was not among them), which may itself indicate a genuine gap rather than an unsearched one, though this has not been confirmed with a dedicated Italy-focused search.

## Management Culture / Legislative Context

**Not researched this session.** Italy is known (from general knowledge, not yet sourced in this study) to have had breed-specific legislation historically (a "dangerous breeds" list, later repealed nationally in 2009 in favour of an "any dog can be dangerous" owner-responsibility framework) -- this is stated here as an unsourced note/lead only, per the project's "never invent data" rule, and must be properly sourced before being used in the final report. A dedicated search for Italy's leash-law/training-requirement/management-culture history is a future-session target.

## Data Gaps
- No national (only regional, Sicily) bite-hospitalisation rate located.
- Shelter/surrender data with an isolated "behaviour" category: not located, one search attempt made.
- Behavioural-problem prevalence / C-BARQ data: not yet searched.
- Management-culture/legislative history (leash laws, breed legislation history, training requirements): not yet searched, though a plausible unsourced lead (2009 national BSL repeal) is noted above for future verification.
- ~~The "Fatal Dog Attacks in Italy 2009-2025" national registry paper (MDPI) is identified but not extracted~~ **RESOLVED same session** -- see the full extraction above. A genuinely national dataset, though media-sourced rather than administrative/hospital-record-based (a different, less-verified data-collection method than this study's other bite/fatality sources, worth remembering when weighing its findings).

## Sources Log (to be mirrored into data-sources.md)
- Alberghina et al. 2023, Frontiers in Veterinary Science, via PMC (fetched by direct device-side curl after the WebFetch tool hit a session usage limit) -- [quality: A]
- "Fatal Dog Attacks in Italy (2009-2025)," MDPI Animals 2025, EXTRACTED via PMC12729952 mirror (direct device-side curl, same session) -- [quality: A]
- RandAgiamo Umbria shelter-adoptability pilot, PMC4598705 -- identified, not extracted (does not answer the surrender-reason question this study needs)

**Population scope note:** the Sicily DBIH data is **[Scope: mixed/unclear]** -- Italian hospital-discharge coding for dog-bite injuries does not distinguish whether the biting dog was owned/household or stray, unlike this study's household-only survey-based sources elsewhere.

# Urban vs. Rural — Variable File
> Started Session 11. Consolidates rural/urban and deprivation-gradient bite/injury data that was already present but scattered across USA.md, Australia.md, UK.md, and (new this session) New-Zealand.md, per the note in variables/README.md. This is a Core-Metric-2-adjacent (bite incidence) explanatory/contextual variable, not a management-culture law/policy variable like most other files in this folder — it sits closer to behavioural-problem-prevalence.md's role (consolidating an existing cross-cutting pattern) than to dog-trainer-regulation.md's (a single tracked policy).

## The pattern, stated up front
Every country in this study with a published urban/rural OR deprivation breakdown shows the SAME direction: bite/injury rates are HIGHER in rural areas and in more socioeconomically deprived areas, never the reverse. This is now a 4-country convergent finding (USA, Australia, UK, New Zealand) — worth treating as a genuine cross-country pattern for Phase 5, not a coincidence in any one dataset. **However, the underlying causal mechanism is not established by any of these sources** — plausible candidate explanations (not yet tested by any source in this study) include: reduced veterinary/behavioural-referral access in rural and deprived areas (see the still-unstarted veterinary-access.md), larger/more free-roaming dog populations in rural settings, different dog-breed/working-dog mixes, less containment infrastructure (fencing), lower uptake of formal training, or simply different injury-reporting/healthcare-seeking behaviour by region. Flagging this explicitly so the pattern is not overstated as already-explained.

## United States
**Source: AHRQ (Agency for Healthcare Research and Quality) 2010, cross-referenced from data/by-country/USA.md — [quality: A, government primary]**
| Metric | Figure | Year |
|--------|--------|------|
| Rural vs urban bite injury rate | Rural areas 4x higher than urban | 2010 |

No further demographic or regional breakdown located in USA.md beyond this headline multiplier.

## Australia
**Source: AIHW, cross-referenced from data/by-country/Australia.md — [quality: A, government primary]**
| Metric | Figure | Year |
|--------|--------|------|
| Rural vs urban rate | Rural rates "significantly higher" than urban (no specific multiplier stated in the source as logged) | Ongoing (AIHW National Hospital Morbidity Database) |

**Gap:** the Australia.md file logs this finding without a specific rural/urban multiplier — a future session could return to the AIHW source to see if a precise figure is available, to make this row comparable to the USA's 4x and UK/NZ's deprivation multipliers below.

## United Kingdom
**Source: NHS Digital 2014, cross-referenced from data/by-country/UK.md — [quality: A, government primary]**
| Metric | Figure | Year |
|--------|--------|------|
| Deprivation gradient (admission rate, most vs least deprived areas) | 3x higher | 2014 |
| Geographic variation, highest region | Merseyside, 32.2 per 100,000 | 2014/15 |
| Geographic variation, lowest region | Kent/Medway, 7.3 per 100,000 | 2014/15 |
| Regional spread (highest/lowest ratio) | ~4.4x | 2014/15 |

## New Zealand
**Source: Duncan-Sutherland et al. 2022, NZMJ — extracted Session 11, cross-referenced from data/by-country/New-Zealand.md — [quality: A, national ACC-claims + hospital-discharge data]**
| Metric | Figure | Period |
|--------|--------|--------|
| Deprivation gradient, ACC claims (decile 10 vs decile 1) | 3.38x higher | 2014-2019 |
| Deprivation gradient, hospitalisations (decile 10 vs decile 1) | 3.97x higher | 2014-2019 |
| Regional variation, highest territorial authorities | Opotiki (695.7 per 100,000), Kawerau (641), Far North (497.7) | 2014-2019 |
| Regional variation, lowest territorial authorities | Wellington City (116.0 per 100,000), Palmerston North (104.6) | 2014-2019 |
| Regional spread (highest/lowest ratio) | ~6.6x (Opotiki vs Palmerston North) | 2014-2019 |

**Note on rural/urban framing:** the underlying paper reports this as a deprivation and territorial-authority breakdown, not an explicit rural/urban binary — but the specific high-incidence areas named (Opotiki, Kawerau, Far North) are predominantly rural/provincial New Zealand districts, while the low-incidence areas (Wellington City, Palmerston North) are urban centres, so this is presented here as consistent in direction with the USA/Australia rural>urban pattern, with the caveat that "deprivation" and "rural" are related but not identical variables, and this study has not independently disentangled them.

## Related but distinct: housing type (not strictly rural/urban)
**Source: Meyer et al. 2023, Denmark — cross-referenced from variables/behavioural-problem-prevalence.md**
Apartment living was associated with HIGHER fear-problem prevalence than houses/farms in this Danish owner-survey study. This is a housing-DENSITY finding, not a geographic rural/urban or deprivation finding, and it measures a behavioural-PROBLEM-prevalence outcome rather than a bite/injury rate — logged here as a related but analytically distinct data point, not combined with the rows above.

## Countries with no urban/rural or deprivation breakdown located
Germany, Austria, Canada, France, Netherlands, Japan, Norway, Sweden, Denmark (bite data specifically -- Denmark's apartment finding above is a behaviour-prevalence finding, not a bite-rate one). Not yet searched specifically for this variable as of Session 11 -- this file was built by consolidating already-extracted data per variables/README.md's original instruction, not by launching new country-by-country searches this session. A dedicated pass for these countries is a reasonable future-session target.

## Data Gaps
- No source in this study has tested WHY the rural/deprivation pattern exists (see "The pattern, stated up front" above) -- this is an analytical opportunity for the Phase 5 discussion, not a resolved mechanism.
- Australia's rural/urban finding lacks a specific multiplier (unlike USA, UK, NZ) -- a future session could attempt to locate one.
- No source yet combines rural/urban status WITH this study's own management-culture variables (training uptake, leash-law strictness, off-leash access) to see whether management-culture differences themselves vary by rural/urban setting -- a genuinely novel cross-variable analysis this study could attempt in Phase 5 given the data now in hand.
- Nine of this study's ~14 countries have no urban/rural or deprivation breakdown located at all (see list above).

## Sources Log (to be mirrored into data-sources.md)
- AHRQ 2010, via data/by-country/USA.md (already logged in data-sources.md from an earlier session)
- AIHW, via data/by-country/Australia.md (already logged in data-sources.md from an earlier session)
- NHS Digital 2014, via data/by-country/UK.md (already logged in data-sources.md from an earlier session)
- Duncan-Sutherland et al. 2022, NZMJ (logged in data-sources.md this session, Session 11)

**Population scope note:** all bite/hospitalisation entries in this file inherit the population-scope tag already assigned to their source in the relevant by-country file ([Scope: mixed/unclear] for USA, Australia, UK, and New Zealand's underlying data) -- this file does not independently re-verify scope, it consolidates already-scoped figures.

# Variable: Breed-Specific Legislation (BSL) -- Consolidated Dated Timeline
> Consolidates BSL history scattered across the by-country files into one cross-country timeline, per the temporal-linkage methodology. Use this file (not memory of the by-country files) when matching a metric data point to the BSL regime in force at that time.

---

## United Kingdom
| Date | Change | Detail | Source |
|------|--------|--------|--------|
| 1991 | Dangerous Dogs Act passed | Banned/restricted 4 types: Pit Bull Terrier, Japanese Tosa, Dogo Argentino, Fila Brasileiro (exact staggered addition dates for the latter 3 not independently re-verified this session -- carried over from prior session's UK.md) | Carried over from UK.md (prior session) -- [quality: A, primary UK statute] |
| 1 Feb 2024 | XL Bully added -- guidance published | | GOV.UK official guidance -- [quality: A] |
| 31 Jan 2024 | Certificate of Exemption application window closed | Owners needed to have applied by this date to keep an existing XL Bully legally | GOV.UK -- [quality: A] |
| 30 Jun 2024 | Neutering deadline, dogs 12+ months | | GOV.UK -- [quality: A] |
| 31 Dec 2024 | Neutering deadline, dogs 7-11 months | | GOV.UK -- [quality: A] |
| 30 Jun 2025 | Neutering deadline, dogs under 7 months | | GOV.UK -- [quality: A] |
| 30 Jun 2026 | Third-party liability insurance requirement window ends | | GOV.UK -- [quality: A] |
| 1 Nov 2026 | New child-supervision rule takes effect | | GOV.UK -- [quality: A] |

**Temporal-linkage significance:** the XL Bully ban was a direct legislative response to the 2023 fatality spike documented in UK.md's "Key Sudden Shifts" table (2 fatalities in 2019 -> 15-20+ in 2023). This is one of the cleanest cause-and-effect regulatory timelines in the whole dataset -- a metric shock (2023 fatalities) followed within months by a specific, dated legislative response (Feb 2024 guidance, phased through 2026). Any UK metric data point from 2024 onward must be read as falling inside a materially different BSL regime than 2023 and earlier -- this is the single most important within-country regime break in the entire study.

## Netherlands
| Date | Change | Detail | Source |
|------|--------|--------|--------|
| 2009 | Pit Bull-type BSL repealed | Following evidence review showing no bite-reduction benefit; post-repeal bite statistics (per Cornelissen & Hopster 2010, ~2008-2010) did not significantly worsen | Cornelissen & Hopster 2010 (carried over, prior session) -- [quality: A/B] |

**Temporal-linkage significance:** the Cornelissen & Hopster 2010 bite data (Netherlands.md) was collected almost immediately AFTER this repeal, making it a genuinely useful "before/after" natural experiment data point -- but the "before" (pre-2009) baseline bite rate was not located this session, so the comparison remains one-sided. Flagged as a specific, well-defined future research target: locate a pre-2009 Dutch bite-rate baseline to complete this comparison.

## Denmark
| Date | Change | Detail | Source |
|------|--------|--------|--------|
| 1 Jul 2010 | Danish Act on Dogs -- 13-breed ban introduced | Pit Bull Terrier, Tosa Inu, American Staffordshire Terrier, Fila Brasileiro, Dogo Argentino, American Bulldog, Boerboel, Kangal, Central Asian Shepherd Dog, Caucasian Shepherd Dog, South Russian Shepherd Dog, Tornjak, Sarplaninac | VisitSonderjylland (regional tourism/government-adjacent guide) -- [quality: B, not cross-checked against the primary Danish statute text this session] |
| 17 Mar 2010 | Cutoff date for dogs acquired before the ban | Dogs owned before this date permitted entry/retention under leash+muzzle conditions, EXCEPT Pit Bull Terrier and Tosa Inu (no grandfathering for these two) | Same source -- [quality: B] |

**MAJOR UPDATE (Session 4):** a peer-reviewed time-series intervention study directly evaluated this law's effect on bite rates in Odense, Denmark:

| Detail | Finding | Source |
|--------|---------|--------|
| Study period | 1 Jan 2002 - 31 Jun 2015 (13.5 years, spanning the 2010 law) | Nilson et al. (or similar authorship -- exact author names not extracted this session), PLOS ONE, doi:10.1371/journal.pone.0208393 -- [quality: A, peer-reviewed] |
| Method | ARIMA time-series modelling (controls for secular/pre-existing trends), not a naive before/after comparison | Same source |
| Raw counts | 2,622 total hospital-treated dog bites (1,748 private-space, 874 public-space) over the study period | Same source |
| Naive before/after comparison | Suggested a 15% reduction -- but this is explicitly the WRONG number to use, per the study's own methodology | Same source |
| Rigorous (ARIMA) result | NO statistically significant effect. Private spaces: -7.53% (95% UI: -49.18 to +55.64, i.e. consistent with no effect or even a large increase). Public spaces: +21.63% (95% UI: -36.46 to +105.12) | Same source |
| Conclusion | "Breed-specific legislation seems to have no effect on dog bite injuries" -- the authors recommend non-breed-specific interventions instead | Same source |

**This is one of the single most important findings in the entire dataset for Phase 5.** It is a rigorous, peer-reviewed, methodologically explicit (ARIMA vs. naive before/after) null result for BSL effectiveness, from a country with a clean single-event 2010 law change and a long, symmetric pre/post data window -- exactly the kind of natural experiment this study has otherwise struggled to find. It should be read alongside the Netherlands 2009 BSL-repeal entry above (repeal did not worsen bite stats) as convergent evidence, and the Manitoba BSL study (still not extracted as of Session 3) as a comparison point once that is retrieved. **Flag prominently for the Methods/Findings section of the final report.**

## Norway
| Date | Change | Detail | Source |
|------|--------|--------|--------|
| Not confirmed this session | Dog Act (Hundeloven) and banned-dogs regulation | Currently bans 6 breeds/types: Pit Bull Terrier, American Staffordshire Terrier, Fila Brasileiro, Tosa Inu, Dogo Argentino, Czechoslovakian Wolfdog; wolf-dog hybrids also restricted | Mattilsynet (Norwegian Food Safety Authority, official government body) -- [quality: A for the current list; enactment year NOT confirmed this session -- flagged gap] |

**Correction to prior session's variables table:** dog-trainer-regulation.md previously listed Norway as banning only "Pit Bull." The Mattilsynet primary source confirms 6 breeds/types are currently banned, not 1 -- this is a correction, not new information, and should be treated as superseding the earlier entry.

## Sweden / Finland
No national BSL confirmed in either prior or this session's research (both prior UK.md/variables and this session's searches consistently return "no BSL" for Sweden and Finland). Absence-of-BSL is itself a data point, not a gap, given multiple independent searches have failed to surface one -- but this should get one more confirmation pass against a primary Swedish/Finnish government source before being stated as fact in the final report.

## Germany
State-level, Category 1 dogs prohibited nationally via import restriction (Pit Bull, Tosa, Dogo Argentino, Fila Brasileiro) plus additional state-specific lists -- carried over from Germany-Austria.md (prior session). No new dating research done this session; still flagged as a Phase 2 gap for state-by-state effective dates.

## Austria
State-level, listed breeds (Pitbull, Rottweiler, Dogo Argentino cited in Germany-Austria.md) -- varies by federal state. No new dating research done this session; effective dates per state not yet researched.

## Canada (Manitoba) -- NEW Session 6
Provincial/municipal, not federal -- BSL exists in some Manitoban jurisdictions (pit-bull-type bans), varying by municipality; a province-wide dated timeline was not built, but a major peer-reviewed EFFECTIVENESS study was extracted this session (see data/by-country/Canada.md for the full table):

**Raghavan, Martens et al. (PMID 22753529)** -- a 23-year (1984-2006) population-level study across 16 Manitoba jurisdictions with pit-bull-type bans. Findings (via secondary summary, primary text still inaccessible -- see Canada.md for the quality caveat): provincial dog-bite-hospitalisation rate fell from 3.47 to 2.84 per 100,000 person-years; adjusted models show larger reductions in BSL-adopting jurisdictions (-21.5% overall, -27.4% for under-20s) than non-adopting ones (-18.1% province-wide baseline), but the SIMPLE pre/post comparison was NOT statistically significant. This is the second major BSL-effectiveness time-series study in the dataset (alongside Denmark below) and the two point in different directions -- see the Interpretive Note in variables/management-practices-and-culture.md for the combined Phase 5 framing (the honest read is "genuinely mixed/weak evidence," not a clean verdict either way).

## Australia
State-based, varies significantly (ACT, NSW, QLD, VIC and others have BSL per Australia.md, prior session). No consolidated dated timeline built this session -- flagged as a gap; would need state-by-state legislative research similar to the Victoria breeding-law timeline in variables/breeding-regulation-and-ethics.md.

## USA
No federal BSL; state/local variation, individual municipal ordinances number in the hundreds. Not practical to build a single dated national timeline -- carried over as a structural note from USA.md (prior session), not a gap to fill in the same way as single-jurisdiction countries.

---

## Cross-Country BSL Snapshot at Different Points in the Study Window
> Illustrates why a single "current BSL status" table would be misleading -- the regime itself moved during the 2014-2024 study period for at least 3 of the countries studied.

| Country | BSL status in 2014 | BSL status in 2019 | BSL status in 2024 |
|---------|--------------------|--------------------|--------------------|
| UK | 4 types banned (1991 Act) | 4 types banned (unchanged) | 5 types banned (XL Bully added Feb 2024) |
| Netherlands | Repealed (since 2009) | Repealed | Repealed |
| Denmark | 13 breeds banned (since 2010) | 13 breeds banned | 13 breeds banned (no repeal/change found) |
| Norway | Banned list in force (year of introduction unconfirmed) | Same | 6 breeds/types (current Mattilsynet list) |
| Germany/Austria | State-level lists in force | Same | Same (no change identified) |
| Sweden/Finland | No BSL | No BSL | No BSL |
| Australia | State-based, varies | State-based, varies | State-based, varies (no national consolidation) |
| USA | No federal BSL; local variation | Same | Same |
| Canada (Manitoba) | Municipal pit-bull-type bans in force in some jurisdictions (Winnipeg etc.) | Same | Same (no province-wide consolidation found; effectiveness study covers 1984-2006 only) |

## Data Gaps (Session 6 status -- updated)
- UK 1991 Act's staggered addition dates for Japanese Tosa/Dogo Argentino/Fila Brasileiro not independently re-verified this session
- Danish Act on Dogs text not cross-checked against a primary Danish government source (only a regional tourism-guide source used)
- Norway's Hundeloven/banned-dogs regulation enactment year not confirmed
- Sweden/Finland "no BSL" status not confirmed against a primary government source (currently based on absence of evidence across multiple searches, which is weaker than positive confirmation)
- Germany/Austria state-by-state BSL effective dates
- Australia state-by-state BSL dated timeline
- Pre-2009 Netherlands bite-rate baseline (would complete the before/after BSL-repeal comparison)
- Manitoba/Canada BSL-effectiveness study (Raghavan et al.) extracted only via a secondary, advocacy-adjacent source (dogsbite.org) -- primary text (PubMed/PMC/Cureus/SafetyLit) remains blocked after attempts across two sessions; figures should be re-verified against the primary text or a neutral secondary source (ResearchGate/Academia.edu copies identified, not yet fetched) before being used without caveat in the final report
- No province-wide (as opposed to single-study) Manitoba or other Canadian BSL dated timeline built

## Sources Log (to be mirrored into data-sources.md)
- GOV.UK -- XL Bully ban guidance and dates -- [quality: A]
- VisitSonderjylland -- Danish Act on Dogs -- [quality: B]
- Mattilsynet (Norwegian Food Safety Authority) -- current banned breed list -- [quality: A]
- dogsbite.org -- secondary summary of Raghavan et al. Manitoba BSL-effectiveness study -- [quality: C for this extraction route -- advocacy-organisation summary of an A-grade peer-reviewed study; primary text still inaccessible] (Session 6)

**Population scope note:** BSL applies to owned/household dogs by definition (it restricts ownership/breeding/importation) -- **[Scope: household-only]** for the entire file.

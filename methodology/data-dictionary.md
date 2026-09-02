# Data Dictionary & Dataset Guide
> Added Session 5, at the user's request: this study is meant to be reviewed and refreshed at least annually, and later used to design questionnaires/study criteria for the scientific and dog-professional community. Both uses depend on everyone (a future session, a future collaborator, a future survey designer) understanding EXACTLY what each figure in this dataset is, where it came from, and what it is and isn't comparable to. This file is the single canonical reference for that -- read it before citing any figure in the eventual report.

---

## 1. The three meta-frameworks that apply to every data point in this project

Every figure collected in data/by-country/*.md and every entry in variables/*.md carries (or should carry) three independent tags. They answer three different questions and must not be conflated:

### 1a. Quality tier (WHO produced it, and how rigorously)
Defined originally in data-sources.md:
- **A** = peer-reviewed academic study OR primary government source (a national statistics office, a ministry, an official legislation database)
- **B** = organisation/charity/industry-body report with a stated methodology (e.g. a national kennel club survey, an animal welfare charity's annual report)
- **C** = survey/secondary/aggregator source, or a source whose primary methodology could not be independently verified

Quality tier is about SOURCE RELIABILITY. A high tier does not mean the underlying data is comparable to another country's data -- see 1b and 1c.

### 1b. Population scope tag (WHAT population it actually measures)
Introduced Session 2, because the original study brief specifically scopes this project to captive/household dogs, not strays or free-roaming dogs:
- **[household-only]** -- the source is restricted, by construction (e.g. an owner-surrender shelter category, a liability insurance claim, a veterinary referral) or by verified national context (e.g. a country with an independently confirmed near-zero stray population), to owned dogs
- **[mixed/unclear]** -- the source does not specify, or plausibly captures both owned and non-owned dogs (most national bite/hospitalisation statistics fall here, since ICD-10 W54 coding does not record ownership status)
- **[includes-strays]** -- confirmed to include free-roaming/community dogs

A figure can be quality-A and STILL be population-scope-[mixed/unclear] -- these are independent axes. CDC hospitalisation data, for instance, is A-grade (US federal government data) but scope-[mixed/unclear] (it doesn't distinguish an owned dog's bite from a stray's).

### 1c. Temporal validity (WHEN it was collected, and what regime was in force then)
Introduced Session 2, because law/policy changes within single countries during the study's own 2014-2024 window (UK's 2024 XL Bully ban, Germany's 2022 Tierschutz-Hundeverordnung, Austria's 2026 national competency law) mean a "current laws" snapshot would misdate older metric data:
- Every metric figure is logged with its OWN collection year(s)
- Every law/policy entry in variables/*.md is logged as a dated timeline, not a current-state snapshot
- **Rule: match a metric to the variable-state that was in force during THAT metric's collection window, never to 2026's rules, unless the metric itself is from 2026.**

---

## 2. What each Core Metric actually measures (and the comparability ladder)

The study brief names three core metrics. In practice, NONE of them is measured the same way twice across the countries in scope -- this section makes explicit what rung of measurement severity each country's figure sits on, because "bite rate" alone is not a well-defined, comparable quantity without this.

### 2a. Bite incident rate -- the severity ladder
Ordered from least to most severe / most to least inclusive of minor incidents:
1. **All self-reported bites (any severity)** -- e.g. Netherlands' Cornelissen & Hopster 2010 internet survey (~830/100,000). Captures the largest population of incidents but relies on self-report and recall.
2. **GP/primary-care-treated bites** -- e.g. part of the same Dutch study (~40,000/yr treated at GP).
3. **Emergency Department (ED) visits/attendances** -- e.g. USA's HCUP NEDS data, the Halifax (Canada) ED study. Captures bites serious enough to seek emergency care but not necessarily admitted.
4. **Hospital ADMISSIONS/hospitalisations** -- e.g. UK NHS HES (ICD-10 W54), Australia AIHW, the pre-study-window Canada CHIRPP figure. This is the rung the UK-Australia comparison in this project's "Critical Methodological Finding" is built on, and it is the ONLY rung with a genuinely comparable multi-country pair so far.
5. **Fatalities** -- e.g. CDC WONDER (USA), ONS (UK), Sarenbo & Svensson 2021's Eurostat W54 fatality dataset (13 European countries). The narrowest, most severe rung -- but also the most reliably counted (a death is hard to miscode or under-report relative to a minor bite), which is WHY it's the only rung with genuine wide multi-country coverage (Europe-wide).
6. **"Serious incidents" (a national administrative category, not a clinical one)** -- e.g. Japan's Ministry of Environment figure (4,208 in 2015). This is NOT equivalent to rung 3 or 4 -- it's a distinct administrative/reporting category specific to Japan's system and should never be placed on the same axis as another country's ED or hospitalisation figure without that caveat restated.

**Practical rule for the final report:** never plot or compare two countries' bite figures without first checking which rung of this ladder each one sits on. The UK/Australia hospitalisation comparison is valid because both sit on rung 4 with matching ICD-10 W54 coding. Almost no other pair in this dataset currently has that property.

### 2b. Behaviour-related shelter surrender/relinquishment rate
This metric hides at least three further definitional variations, independent of the severity-ladder concept above:
- **Denominator differs:** some sources report behaviour's share of ALL shelter intake (strays + surrenders combined, e.g. Australia's RSPCA overall figures); others report behaviour's share of OWNER SURRENDERS specifically (e.g. USA's SAC "owner surrender" category, UK's Dogs Trust). These are not the same denominator and must not be directly compared.
- **"Behaviour" itself is coded inconsistently:** some studies lump all behaviour-related reasons into one category; others split aggression/fearfulness/house-soiling/separation-anxiety separately (see UK.md's note on the Dogs Trust 6.07% vs. Diesel et al. 34.2% discrepancy -- these measure genuinely different things, not a data error).
- **National systems are architecturally different**, not just differently measured: the Netherlands' no-kill, no-stray, government-policed shelter system is not directly comparable in STRUCTURE (not just numbers) to the USA's mixed no-kill/open-admission system or Japan's hokensho (public health centre) model. A percentage from one system cannot be read as equivalent to the same percentage in another.

### 2c. Referral rate to behaviour professionals
The thinnest metric in the entire dataset. No country publishes a NATIONAL rate. What exists instead:
- Single-clinic or single-service caseload studies (USA: PMC8909650, one university veterinary behaviour referral service)
- Survey-based estimates of vet referral PRACTICE, not population-level referral RATE (Ireland/UK: Duggan et al. 2018, >50% of practices say they refer)
- One genuine population-level estimate exists: Australia's VetCompass-derived 11% of "undesirable behaviour" cases referred (PMC7918417) -- this is flagged in Australia.md as "one of the only published figures for behaviour referral practice from any country in this study" and should be treated as a landmark data point, not a routine one.

### 2d. Supplementary metrics (insurance claims, euthanasia-for-behaviour)
Useful as corroborating signal but each has its own denominator problem: insurance claims (USA) are conditional on having liability insurance at all (a self-selected, likely wealthier population); euthanasia-for-behaviour figures conflate "behaviour problem" with "shelter capacity/resource constraint" in ways the sources themselves rarely disentangle.

### 2e. Broader behavioural-problem prevalence (Session 8 addition) -- the measurement-threshold problem
Core Metric 5 (variables/behavioural-problem-prevalence.md) exists because bites are one narrow, severe subtype of a much wider range of ways a dog can fail to integrate successfully into a household -- separation anxiety, chronic fearfulness, destructive behaviour, house-soiling, compulsive behaviour, and non-bite aggression (growling, snapping, lunging) all matter and none of them require a bite to have occurred. This metric has its OWN comparability problem, distinct from (and in some ways worse than) the bite severity ladder in 2a: **the same underlying reality produces wildly different headline prevalence numbers depending purely on how the survey question is framed.** Four studies in this dataset illustrate the point directly: USA (Dog Aging Project) reports 99.12% of dogs have "a behaviour problem" because it counts ANY non-zero score on a 0-4 severity scale as qualifying; Finland (Salonen/Sulkama 2020) reports 72.5% using a clinically-informed any-of-7-traits threshold; Denmark (Meyer 2023) reports 34% using the owner's own subjective "do you consider this a problem" judgement; Australia (VetCompass) reports 29.7% but of a completely different denominator (deaths, not living-population prevalence). **The rule for this metric is therefore even stricter than for bites: never state a headline "X% of dogs in country Y have behaviour problems" figure without stating, in the same sentence, what threshold/instrument produced it.** Prefer specific named sub-category prevalence (e.g. "X% show separation-related behaviour") over the headline "any problem" percentage wherever both are available, since narrower categories carry somewhat less definitional baggage, though still not full standardisation across countries. A genuinely comparable cross-country picture for this metric would require the SAME instrument (e.g. pure C-BARQ) applied in multiple countries -- this has not yet been assembled in this dataset (see variables/behavioural-problem-prevalence.md Data Gaps) but is flagged as high-value future work, since the C-BARQ instrument itself has reportedly been used in 70+ published studies internationally.

---

## 3. What each Variable category captures (and why it was chosen)

| Variable file | What it captures | Why it's a candidate explanatory variable |
|----------------|-------------------|---------------------------------------------|
| population-density-and-ownership.md | People/km2 (structural, near-static) + dog population & % household ownership (a genuine 2014-2024 trend variable, especially the pandemic surge/decline) | Tests the naive "crowding causes conflict" hypothesis (already found NOT to hold cleanly -- see that file's Interpretive Flag) and provides the denominator context for reading any per-capita metric |
| breeding-regulation-and-ethics.md | Breeder licensing/registration law, "torture breeding" (Qualzucht-style) bans, third-party sale bans (Lucy's Law-style) | Tests whether SUPPLY-SIDE regulation (who is allowed to breed, and how) correlates with downstream behaviour outcomes -- a genetics/early-life-conditions pathway, distinct from the management-culture pathway below |
| breed-legislation-timeline.md | BSL introduction/repeal dates, and (Session 4) the one rigorous peer-reviewed effectiveness study found (Denmark, null result) | Tests the specific, narrow hypothesis that RESTRICTING SPECIFIC BREEDS reduces bite rates -- current evidence (Denmark null result, Netherlands repeal not worsening rates) leans against this hypothesis, which is itself a reportable finding |
| dog-trainer-regulation.md | Trainer licensing (or its absence), owner-education/competency mandates, e-collar/prong-collar bans | Tests whether regulating the TRAINING INDUSTRY and mandating owner competency correlates with outcomes -- a knowledge/skill pathway |
| management-practices-and-culture.md | Crate/home-confinement rules, leash-law strictness and off-leash access structure, minimum exercise mandates | Added Session 3 at the user's explicit correction -- this is now understood to be the PRIMARY explanatory variable category the study is actually trying to test: not "what's banned" but "how are dogs actually managed day to day," a lifestyle/husbandry pathway distinct from all four above |

---

## 4. Glossary of recurring terms/abbreviations
- **ICD-10 W54** -- the international disease/injury classification code for "bitten or struck by dog." Used by NHS HES (UK), AIHW (Australia), and the Eurostat/Sarenbo & Svensson fatality dataset. Its consistent use across UK/Australia/Eurostat-Europe is WHY those are the few genuinely comparable data points in this study.
- **HES** -- Hospital Episode Statistics (UK, NHS Digital)
- **AIHW** -- Australian Institute of Health and Welfare
- **SAC** -- Shelter Animals Count (USA national shelter database)
- **CHIRPP** -- Canadian Hospitals Injury Reporting and Prevention Program
- **CIHI** -- Canadian Institute for Health Information (a still-unretrieved target, distinct from CHIRPP)
- **FEDIAF** -- the European pet food industry federation; source of the main cross-European dog-ownership dataset used in this project
- **BSL** -- Breed-Specific Legislation
- **Qualzucht** -- German legal term, "torture breeding" -- breeding that causes hereditary suffering
- **Sachkundenachweis** -- German/Austrian term for a proof-of-competency certificate for dog owners
- **Divagation** -- French legal term for a dog being beyond its owner's control/recall range (the basis of France's leash-law-adjacent standard)
- **Bandtvang** -- Norwegian term for the seasonal (1 Apr-20 Aug) national leash requirement
- **Losloopgebieden** -- Dutch term for municipally-designated off-leash zones
- **Hokensho** -- Japanese public health centres, historically the point of intake for both owner-surrendered and stray dogs

---

## 5. What this dictionary is FOR (forward-looking)
This file exists so that three future uses of the project all start from the same shared, correct understanding of the data:
1. **Annual refresh** (see methodology/annual-update-protocol.md) -- anyone updating a figure next year needs to know which rung/tag/scope it sits at BEFORE replacing it with a newer number, so the new number is filed at the same level of precision, not silently upgraded or downgraded in comparability.
2. **Questionnaire/study-criteria design for the scientific and dog-professional community** (see methodology/future-deliverables.md) -- the gaps and inconsistencies catalogued here (no country has a national referral rate; "behaviour" is coded differently everywhere; no rung-4 bite data exists for most countries) are themselves the starting point for what a purpose-built survey instrument should ask, because they identify exactly what published data currently CANNOT tell us.
3. **The eventual interactive HTML review tool** (see methodology/future-deliverables.md) -- any UI that lets a viewer filter/compare figures needs this dictionary's tags (quality tier, scope, temporal validity) as first-class filterable/visible fields, not decorative footnotes, or the tool would silently re-introduce the comparability errors this project has worked to avoid.

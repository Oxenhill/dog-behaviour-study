# Future Deliverables -- Planned, Not Yet Built
> Added Session 5. Both items below were explicitly requested as FUTURE work by the user ("put it aside for future and plan for it"). Nothing in this file should be built until the user asks. This file exists so the plan survives between sessions and so current data-collection work is done in a way that doesn't have to be redone to support these later.

---

## A. Interactive HTML review tool (planned, not built)

### Purpose
A way to browse and compare findings visually, rather than reading through markdown files -- for the user's own review, and eventually potentially for sharing with the scientific/dog-professional audience mentioned below.

### What it should show (draft concept, subject to revision when actually scoped)
- **Per-country cards or a comparison table**: the 3 core metrics + supplementary metrics, side by side, WITH their quality tier, population-scope tag, and collection year visibly attached to every figure (per methodology/data-dictionary.md's rule that these tags must be first-class, not footnotes)
- **A "severity ladder" visual for bite data specifically**: since methodology/data-dictionary.md section 2a establishes that bite figures sit at different measurement rungs (fatality / hospitalisation / ED visit / GP visit / self-report / "serious incident"), the tool should make it visually obvious which rung each country's figure occupies, so a viewer cannot accidentally compare a UK hospitalisation rate to a Japan "serious incident" count as if they were the same thing
- **Variable timelines rendered as an actual timeline/Gantt-style view**: population-density-and-ownership.md, breeding-regulation-and-ethics.md, breed-legislation-timeline.md, and management-practices-and-culture.md are all already structured as dated tables specifically so they COULD render this way
- **A live "gaps map"**: which country/metric/variable cells are filled, partially filled, or empty -- directly derived from every file's "Data Gaps" section, so the tool doubles as a research-planning view, not just a results view
- **A "what changed since last year" view**, once methodology/annual-update-protocol.md has been run at least twice and there's a real time series to show

### Build approach (when the time comes)
- This session has access to the Artifact tool, which is the natural home for this (a hosted, shareable, updatable HTML page)
- The prerequisite is DATA STRUCTURING: the underlying content currently lives as prose-heavy markdown tables, which is right for a human researcher reading and citing sources but not directly consumable by an HTML page. Before building the tool, the figures (not the narrative/caveats, which should stay in the markdown files as the source of truth) should be extracted into a structured format (e.g. one JSON or CSV file per metric, keyed by country + year + quality tier + scope tag) that the HTML can read. This extraction step is itself future work, not something to do preemptively now while the underlying research is still actively changing week to week.
- Recommend building it only once a reasonable first pass of Phase 4 (variables) and Phase 2 (metrics) is done, so the tool reflects a stable-enough dataset to be worth the structuring effort -- rebuilding a data pipeline every session while the underlying files are still being actively extended is wasted work.

---

## B. Questionnaire / study-criteria design for the scientific & dog-professional community (planned, not built)

### Purpose
Stated by the user: use this project's findings to design a survey/questionnaire that could be put out to the scientific community and dog professionals (trainers, behaviourists, vets) -- presumably to gather PRIMARY data this project has repeatedly found does not exist in published secondary sources.

### Why the current project structure already sets this up well
Every "Data Gaps" section across every country and variable file is, in effect, a list of things published data cannot currently answer. That list is the natural starting point for questionnaire design -- a survey exists specifically to collect what secondary sources don't have. Some concrete examples already logged in this dataset that map directly onto candidate survey questions:

| Logged gap | Candidate questionnaire angle |
|-------------|-------------------------------|
| No country publishes a national behaviour-referral rate (methodology/data-dictionary.md 2c) | Ask practising vets/behaviourists directly: what share of your caseload is behaviour-related, and what share of THOSE cases get referred onward? |
| "Behaviour" as a shelter surrender reason is coded inconsistently across countries (2b) | A standardised, piloted coding instrument for surrender REASON, administered prospectively to shelters across multiple countries, would directly fix the comparability problem this project keeps flagging |
| Management-practices-and-culture.md's laws describe what's LEGALLY required, not what's ACTUALLY practised or how strictly enforced | Ask dog owners/trainers directly: do you crate your dog at home? For how long? Is your local off-leash rule actually enforced? This is the "enforcement reality vs. legal standard" gap explicitly named in that file's Data Gaps section |
| No country has a rigorous BEFORE/AFTER study of an owner-education mandate's effect on outcomes (flagged repeatedly for Germany's Lower Saxony Sachkundenachweis, Austria's Vienna/national requirements) | A prospective or retrospective cohort survey of owners who did vs. didn't take a mandated competency course, tracking self-reported behaviour outcomes |
| No systematic cross-country measure of crate-use PREVALENCE (only legal status is documented) | A simple prevalence survey: "does your dog have a crate; how many hours/day is it used; for what purpose" -- fielded consistently across countries, this alone would fill a real gap |

### Recommended approach (when the time comes)
- Draft the questionnaire only AFTER Phase 4 (variables) and Phase 5 (analysis) are further along, so the questions target the gaps that turn out to matter most for the actual findings, rather than every gap generically
- Design it to be answerable by two distinct audiences separately (practising dog professionals vs. academic researchers), since their vantage points differ -- a trainer can speak to enforcement/prevalence reality, a researcher can speak to what a rigorous study design would need to fix the definitional-inconsistency problems
- Anchor every question explicitly to a named gap in this dataset (per the table above), so the eventual survey has a clear methodological justification trail back to this project, rather than being a generic pet-industry survey

---

## Status
Both items above are PARKED. Do not build either until the user explicitly asks. Revisit this file at that point rather than starting from scratch.

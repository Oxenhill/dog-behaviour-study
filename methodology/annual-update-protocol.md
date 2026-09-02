# Annual Update Protocol
> Added Session 5. This study is designed to be a LIVING document, reviewed and refreshed at least once a year, not a one-off report. This file is the checklist to run each time it's refreshed. Follow it in order; update the "Update Log" at the bottom every time you run it, even a partial run.

---

## Why this is needed
Several of the strongest sources in this dataset are ANNUAL or periodic publications that will have newer editions by the time this is next reviewed:
- Shelter Animals Count (USA) -- annual report
- Dogs Trust Annual Report (UK) -- annual
- AIHW "Injury in Australia" (Australia) -- periodic, updated
- RSPCA Australia Animal Outcomes Report -- annual
- Humane Canada Canadian Animal Shelter Statistics Report -- annual
- FEDIAF Facts & Figures -- periodic (2022 edition used; methodology changes between editions per FEDIAF's own caveat -- check this each time)
- Japan Pet Food Association National Survey on Dog and Cat Ownership -- annual
- Companion Animals New Zealand (CANZ) NZ Pet Data Report -- annual/periodic
- PDSA PAW Report (UK) -- annual
- ZZF/IVH survey (Germany) -- periodic

Beyond the data, LAW itself is actively moving during the study's own edges: the UK's XL Bully rules are on a multi-year phased schedule running through at least Nov 2026; Austria's national owner-competency law was slated for July 2026; an EU-wide cat/dog welfare rule was reportedly adopted around April 2026 (unconfirmed full text as of Session 3/4). A yearly pass is the minimum cadence to keep the "Key Sudden Shifts" and variable timelines from going stale.

---

## The Protocol (run in this order)

### Step 1 -- Re-read the meta-files first
Before touching any data, read (in this order): `_PROJECT_STATE.md`, `methodology/data-dictionary.md`, `data-sources.md`. Do not skip this even if it "was just done a year ago" -- assume nothing is remembered.

### Step 2 -- Check each annual/periodic source (list above) for a newer edition
For each one: has a new edition been published since the version currently cited? If yes:
- Add the NEW figure as a NEW dated row in the relevant country file / variable file -- do NOT overwrite the old figure. This dataset's value increases over time specifically because it becomes a genuine multi-year TIME SERIES per source, which is exactly what Phase 5 (Analysis) and any future questionnaire/study need.
- Tag the new figure with the same quality/scope/temporal rigor as the rules in `methodology/data-dictionary.md` require.
- If a source's METHODOLOGY changed between editions (FEDIAF explicitly warns about this), note that explicitly next to the new figure -- do not silently treat it as a continuous series if the source itself says it isn't.

### Step 3 -- Check named "identified but not extracted" items
Search `_PROJECT_STATE.md`'s Next Action list and every variable/country file's "Data Gaps" section for items marked "identified, not extracted" or "blocked this session." Attempt each ONCE. If still blocked, note the new attempt date and move on -- do not spend the whole annual session re-fighting the same dead URL (this was an explicit, named lesson from Session 2/3 of this project).

### Step 4 -- Check for law/policy changes in the variable timelines
Specifically re-check anything flagged in the variable files as having an upcoming or uncertain effective date:
- Austria's national owner-competency law (was slated July 2026 -- has it taken effect? any outcome data yet, even preliminary?)
- The EU-wide cat/dog welfare rules (April 2026 European Parliament press release -- still unconfirmed full text as of last check -- try again)
- UK XL Bully phased deadlines (child-supervision rule 1 Nov 2026, insurance requirement window ends 30 Jun 2026 -- both now closer/passed by the time of an annual review; check for any enforcement/outcome reporting)
- Germany's 2024 Qualzucht amendment (was proposed with a criticised 15-year transition period -- check final passage status)

### Step 5 -- Re-run the population-scope audit on any NEW source added this cycle
Every new source gets a `[household-only / mixed-unclear / includes-strays]` tag at the point of entry, per the Session 2 standing rule in data-sources.md -- do not let this lapse just because it's an annual habit rather than a fresh-project habit.

### Step 6 -- Update the Phase Tracker and Countries-in-Scope table in `_PROJECT_STATE.md`
Reflect what changed. If a previously-thin country (Canada, New Zealand, France, Germany, Austria, Japan, Scandinavia) has crossed a threshold of having enough data for the main quantitative comparison, move it out of "qualitative only" status explicitly and say why.

### Step 7 -- If the report has already been drafted (Phase 6+) by this point
Check whether any NEW figure or finding from this cycle changes a claim already written into `draft/` or `final/`. A living document's biggest risk is a stale claim sitting next to fresher underlying data -- this step exists specifically to prevent that drift.

### Step 8 -- Log the run
Add an entry to the Update Log below with: date, who/what ran it (session ID or user), which steps were completed, what was found, what's still open. Even a partial run should be logged -- a half-finished update that isn't logged is worse than not starting, because a future reviewer will assume it was thorough.

---

## Update Log
| Date | Steps completed | Key findings | Still open |
|------|-------------------|----------------|--------------|
| (none yet -- this protocol was written Session 5, 2 September 2026, before any annual cycle has occurred) | -- | -- | -- |

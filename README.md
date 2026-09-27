# FDA-2026-N-4699 Docket Monitor

Weekly dashboard tracking public comments and FDA milestones for the **Expedited IND Pilot Program** (Operation TrialBlazer). The RFI comment period closed **August 24, 2026**; FDA **launched the pilot on September 15, 2026** and is taking sponsor–QRI applications through **October 30, 2026**.

## Contents

- `index.html` — self-contained dashboard (KPIs, comment activity, milestone timeline, trade-group watch). Open in any browser, or serve via GitHub Pages.
- `summaries/` — written check summaries.

## Current status (check of Sep 27, 2026)

| Metric | Value |
|---|---|
| Total comments published | 217 (+158 since Jul 28 baseline of 59); docket **closed** Aug 24 |
| Trade-group filings (PhRMA / BIO / large pharma) | **Confirmed** — PhRMA (-0191), BIO (-0150), Pfizer (-0185), Amgen (-0106), Takeda (-0200); plus ACRO, ARM, ASGCT, IQVIA and a broad QRI-candidate field |
| Latest FDA milestone | **Pilot launched Sep 15** — final design; applications open through Oct 30; first cohort of 8–10 sponsor–QRI pairs expected ~Dec 18 |
| Awaited | Application intake through Oct 30; cohort selection Dec 18; longer-term QRI accreditation model |

## Data sources

- Regulations.gov API: `api.regulations.gov/v4/comments?filter[docketId]=FDA-2026-N-4699`
- Docket page: https://www.regulations.gov/docket/FDA-2026-N-4699
- Federal Register mirror: FR docs 2026-12621 (RFI), 2026-13592 (correction), 2026-14672 (extension)
- FDA: Sep 15, 2026 press release + Expedited IND Pilot Program webpage

*Note: regulations.gov API endpoints were intermittently unreachable from this environment during the Sep 27 check; docket data was pulled live via browser session on regulations.gov (full 217-comment pull) with FR cross-verification. Comment "posted" dates are regulations.gov posting dates — the 101-comment Aug 26 wave was received by FDA on/before the Aug 24 deadline.*

# FDA-2026-N-4699 Docket Monitor

Weekly dashboard tracking public comments and FDA milestones for the **Expedited IND Pilot Program Request for Information** (Operation TrialBlazer). Comment period closes **August 24, 2026**.

## Contents

- `index.html` — self-contained dashboard (KPIs, comment activity, milestone timeline, trade-group watch). Open in any browser, or serve via GitHub Pages.
- `summaries/` — weekly written summaries.

## Current status (check of Jul 28, 2026)

| Metric | Value |
|---|---|
| Total comments posted | 59 (+2 since Jul 27 baseline of 57) |
| Trade-group filings (PhRMA / BIO / large pharma) | 0 confirmed |
| Latest FDA milestone | Comment period extended to Aug 24 (FR doc 2026-14672, Jul 21) |
| Awaited | Pilot launch date, QRI eligibility/selection criteria |

## Data sources

- Regulations.gov API: `api.regulations.gov/v4/comments?filter[docketId]=FDA-2026-N-4699`
- Docket page: https://www.regulations.gov/docket/FDA-2026-N-4699
- Federal Register mirror: FR docs 2026-12621 (RFI), 2026-13592 (correction), 2026-14672 (extension)

*Note: regulations.gov was unreachable during the Jul 28 check; counts were verified via the Federal Register's docket metadata sync (Jul 27, 12:55 UTC). New-filer identities pending verification.*

# El Cerrito Finance Check

An independent look at claims about the City of El Cerrito, California's finances, tested against the City's own audited reports and other public data.

- **`index.html`**: overview, summary and sources.
- **`finance-pages.html`**: Part 1, a claim-by-claim check of the [Ira Sharenow's Finance pages](https://irasharenow100.github.io/portfolio/finance/), with interactive charts.
- **`candidates.html`**: Part 2, financial statements by the six 2026 City Council candidates, checked with the same rubric, with Nextdoor screenshots linked from each claim.
- **`v2026-10-20/`**: the site as first published, kept unchanged for reference. See the revisions log on the overview page for what changed.
- **`questions.html`**: Part 3, longer answers: what is driving spending growth, how transfers between funds work, the FY2026 Successor Agency payment, and where the amended budget went unspent.
- **`screenshots/`**: the Nextdoor screenshots. Other residents' names, photos and neighborhoods are blacked out, and the images carry no metadata.
- **`el-cerrito-financial-statements-FY2014-FY2026.xlsx`**: the underlying workbook, covering fiscal years ending June 30, 2014 through 2026:
  - General Fund statements, budget variance by year, and Council-approved budget amendments
  - citywide (governmental activities) statements: capital assets, long-term debt, pensions
  - GASB 44-style statistical schedules
  - Every figure links to a single input table, and tie-out checks confirm the totals match the source documents.

FY2025-26 figures are **unaudited**, from the City's fourth-quarter budget update. They are marked in orange throughout. The audited report for that year is expected in December 2026.

## Sources

All public:

- City of El Cerrito annual audited financial reports (CAFR/ACFR), FY2014–FY2025: <https://www.elcerrito.gov/Archive.aspx?AMID=76>
- City Council agenda packets (Q4 and mid-year General Fund budget updates, budget adoption): <https://elcerritoca.portal.civicclerk.com>
- City budget documents, including the FY2026-27/2027-28 Budget in Brief: <https://www.elcerrito.gov/232/Budget-Financial-Information>
- CalPERS annual valuation reports for the City's Miscellaneous and Safety plans, June 30, 2024 and 2025: <https://www.calpers.ca.gov/documents/el-cerrito-city-miscellaneous-2025/download> and <https://www.calpers.ca.gov/documents/el-cerrito-city-safety-fire-2025/download>
- California State Controller, By the Numbers: city expenditures and revenues per capita, net pension liability: <https://bythenumbers.sco.ca.gov>
- California State Auditor reports 2020-803 and 2024-801: <https://www.auditor.ca.gov>
- U.S. Bureau of Labor Statistics CPI-U, San Francisco-Oakland-Hayward (series CUURA422SA0), via FRED: <https://fred.stlouisfed.org/series/CUURA422SA0>
- September 30, 2026 City Council candidate forum: <https://www.youtube.com/watch?v=OcbA9xazYY0>
- Candidates' public Nextdoor posts and replies, captured October 19, 2026

## Notes

- **Transcription.** Figures were transcribed from the source PDFs and checked against each document's printed totals. Where the City's own reports contain errors or inconsistencies, the workbook notes them in cell comments rather than changing them silently.
- **Folder references.** Workbook notes mention folders such as `../acfr/`; those refer to local copies of the source documents listed above.
- **Recalculation.** The workbook recalculates when opened in Excel.

# Local audit — Amazon_Marketplace_Analytics_Project

## Changes

Repaired standalone ingestion and SQL execution; all five query snapshots match. Rewrote documentation, removed personal promotional links, normalized two filenames, redacted browser/Jira personal labels and removed saved-directory metadata from two Excel files.

## Validation performed

- **PASS** — Amazon_Marketplace_Analytics_Project/scripts/run_analysis.py: Python syntax
- **PASS** — Amazon_Marketplace_Analytics_Project/scripts/validate.py: Python syntax
- **PASS** — Amazon_Marketplace_Analytics_Project/Excel/Amazon_Marketplace_User_Story_Backlog.xlsx: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — Amazon_Marketplace_Analytics_Project/Excel/Amazon_Marketplace_Analytics_Project_Workbook.xlsx: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — Amazon_Marketplace_Analytics_Project/Excel/Amazon_Marketplace_Analytics_Project_Project_Workbook.xlsx: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — Amazon_Marketplace_Analytics_Project/Excel/Amazon_Marketplace_UAT.xlsx: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — Amazon_Marketplace_Analytics_Project/Dashboard/Amazon_Marketplace_Analytics_Dashboard.pbix: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — SQL snapshots: PASS Q01: all 1 result rows match the supplied snapshot; PASS Q02: all 6 result rows match the supplied snapshot; PASS Q03: all 4 result rows match the supplied snapshot; PASS Q04: all 80 result rows match the supplied snapshot; PASS Q05: all 24 result rows match the supplied snapshot; PASS: snapshot reconciliation; not business sign-off or native dashboard validation.
- **PASS** — portable execution: Q01: 1 rows; Q02: 6 rows; Q03: 4 rows; Q04: 80 rows; Q05: 24 rows
- **PASS** — full SQL packs: All SQL files executed successfully with the canonical schema.
- **PASS** — blank ingestion: Invalid input rejected before query execution.
- **PASS** — nonfinite ingestion: Invalid input rejected before query execution.
- **PASS** — fractional ingestion: Invalid input rejected before query execution.
- **PASS** — Amazon_Marketplace_Analytics_Project/Excel/Amazon_Marketplace_User_Story_Backlog.xlsx preservation: All worksheets, formulas, chart parts, styles and other members byte-identical; changed parts: ['xl/workbook.xml']
- **PASS** — Amazon_Marketplace_Analytics_Project/Excel/Amazon_Marketplace_Analytics_Project_Workbook.xlsx preservation: All worksheets, formulas, chart parts, styles and other members byte-identical; changed parts: []
- **PASS** — Amazon_Marketplace_Analytics_Project/Excel/Amazon_Marketplace_Analytics_Project_Project_Workbook.xlsx preservation: All worksheets, formulas, chart parts, styles and other members byte-identical; changed parts: []
- **PASS** — Amazon_Marketplace_Analytics_Project/Excel/Amazon_Marketplace_UAT.xlsx preservation: All worksheets, formulas, chart parts, styles and other members byte-identical; changed parts: ['xl/workbook.xml']
- Archive members and XML were parsed where present; images decoded and screenshots reviewed. Notebook/JSON syntax and local paths were checked.
- No plaintext secret candidates, personal contact emails, promotional GitHub/LinkedIn profile links or machine-home paths were detected in the final scanned text/package content. This is a bounded local pattern scan, not proof that opaque native models contain no sensitive data.

## Remaining limitations

Power BI refresh/DAX and Excel recalculation were not executed. Compressed PBIX DataModel content cannot be fully inspected without the native engine. Source licensing and data redistribution rights remain unconfirmed. The inherited shared Local_System application was not supplied.

## Provenance and execution scope

Original source datasets and SQL are retained. No Git history was present in the five extracted folders. Original Downloads folders match their pre-copy SHA-256 hashes. No GitHub command, authentication, repository creation, commit, push or upload was performed.

Original authorship and legally required notices remain in [ATTRIBUTION.md](ATTRIBUTION.md). Personal UI redactions do not replace author attribution.

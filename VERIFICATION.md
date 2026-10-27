# Verification

Verified locally on October 27, 2026 with Node 24 and Google Chrome.

## Automated checks

`npm test`: 9 tests passed.

The tests cover three mismatches and one aligned control; exclusion of superseded references; a newer proposal not replacing an issued RFI; dimensional compatibility; unit conversion; floating-point tolerance; source-rich clarification drafts; exported dispositions, reference locators and notes; invalid dates/numbers/units/elements; and stable comparison IDs when source order changes.

`npm run build`: passed. Local preview returned HTTP 200.

## Browser workflows

- Opened the main comparison and inspected issued versus observed excerpts.
- Generated a clarification draft and confirmed it contained the project and source references.
- Tried closing a check without a supporting reference: rejected with a specific validation message.
- Recorded a clarification-requested disposition with a reviewer note, reloaded, and confirmed it persisted.
- Filtered to Aligned and verified one result; opened it and confirmed the 0.9 m / 900 mm pair had no numerical discrepancy.
- Entered a new 900 mm DR-08 observation with author, locator, date, and source excerpt; the queue grew from 4 to 5 and correctly produced another aligned comparison.
- Inspected and removed that disposable local test observation; queue returned to 4.
- Opened the source register, including both the superseded P02 and current issued C03 revisions.
- Exercised review-pack export. The app showed export-prepared feedback. Completed download on disk was not independently verified; generated export content is tested and included under examples/.
- At 390 x 844, document width equaled viewport width (390 px). Source dialog width was 360 px, without horizontal page overflow. Escape dismissed the dialog.
- No captured browser console errors or warnings in the final check.
- Captured three real browser screenshots from localhost and visually inspected the main comparison and review pack.

No live Cogram integration, AI extraction accuracy, production scalability, professional design compliance, or commercial impact was tested or claimed.

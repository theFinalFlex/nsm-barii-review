# NSM Barii research package

Evidence collected through **2026-09-06**. This cleaned edition organizes the completed research; **the archive review remains incomplete**. Cleaning did not add new media review or runtime verification.

- [Report](report.md): synthesis and qualified conclusions.
- [Project catalog](project-catalog.md): all 28 repositories plus unmatched builds and prototypes.
- [Timeline](timeline.md): dated milestones; source publication and repository events remain distinct.
- [Evidence CSV](evidence.csv): 105 findings, each with a stable evidence ID and source item ID.
- [Coverage CSV](coverage.csv): 165 inventory/reference records and their actual review status.
- [Open questions](open-questions.md): unresolved claims, access gaps and precise continuation queues.
- [JSON data](data.json): the same two tables plus coverage totals for programmatic use.

## Reading the data

CSV files use UTF-8 with a byte-order mark for spreadsheet compatibility. JSON uses UTF-8. Empty dates mean unknown; they are not estimated. `date_basis` distinguishes publication, repository creation, merge and review-observation dates. `reviewed_as_of` is the cutoff date for the saved evidence, not a claim that every source was freshly rechecked on that day.

Join `evidence.source_item_id` to `coverage.item_id`. Stable IDs derive from source identity and claim context. YouTube watch and Shorts forms of the same video URL share one coverage identity. Hidden playlist slots remain separate records with unknown video identities. IDs are identifiers, not ranking or confidence scores.

`self-reported` records creator statements or published descriptions. `demonstrated` is limited here to the static source/page observations named in `verification_scope`; it does not mean a security tool was run. `independently corroborated` means the specific fact is supported by an external primary record or platform metadata. `disputed` preserves a source discrepancy. `inference` labels reviewer interpretation. Read each caveat with its claim.

`transcript_status=fully_read` means the full available caption text was read; some captions contain only music. It never means full video playback, visual verification or a complete review of comments and links. All 26 livestreams still need full review. The 12 Instagram captions represent the public slice discovered, and no Discord history was reviewed.

## Coverage totals

28 repositories; 21 regular videos, 35 Shorts and 26 livestreams; 52 full available transcripts read; 12 Instagram captions read; zero Discord messages reviewed. Four playlists, two community posts, two unresolved unavailable playlist slots, highlights and supporting references have separate ledger records. Ledger rows count resources, not fully reviewed works.

This package contains synthesis and paraphrases rather than full transcripts, private conversations or executable security tools.

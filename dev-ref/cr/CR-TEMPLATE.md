# CR-nnnn — <Title>

| Field | Value |
| :--- | :--- |
| CR number | CR-nnnn |
| Title | <short, imperative> |
| Class | C (Change) |
| Safety-relevant | Yes / No (J.3) |
| Author | <name> |
| Created | yyyy-MM-dd |
| State | Draft |
| Based on POR | V<nn> |
| Decision | <Approved / Rejected / Deferred>, yyyy-MM-dd, <approver> |
| Merged in CAD | V<nn> |
| Released in | <x.y.z> (filled in at release, Appendix L.4) |

## 1. Summary
One or two sentences: what changes, for whom.

## 2. Reason
The problem or need. Who asked for it, and what happens if nothing changes.

## 3. Current POR
The requirement text as it stands, quoted with its IDs (FR-xx.n, NFR-xx, Appendix D, ...).

## 4. Proposed change
The new or changed requirement text, written as it will appear in the CAD.
New IDs take the next free number (J.1). Withdrawn IDs are listed explicitly.

## 5. Impact
| Area | Impact (none / describe) |
| :--- | :--- |
| Requirements (FR / NFR) | |
| UI screens and navigation (Appendix D) | |
| Language packs (en, zh-TW) | |
| Settings keys (Appendix B) | |
| Data formats (Appendix A: cache, journal, CSV) | |
| Exit codes (Appendix E) | |
| Platform API catalogue (Appendix G) | |
| Hard constraints (§2.4, NFR-01–03) | |
| Tests (§6.2) | |
| HIL checklist (§6.4) | |
| Documentation (README, CHANGELOG, CLAUDE.md) | |
| Assumptions / open issues (Appendix I) | |

## 6. Risks
What could go wrong, especially data loss, writes outside the allowed locations,
network access or elevation. How each risk is prevented or detected.

## 7. Alternatives considered
Each alternative with the reason it was not chosen. "Do nothing" is always one.

## 8. Acceptance criteria and tests
New or changed TC cases (ID, requirement, test, criteria).

## 9. Implementation and verification record
Filled in during In progress / Implemented: commits, test results, HIL results, date.

## 10. Dependencies
Other CRs, OI items or assumptions this CR depends on or affects.

## 11. History
| Date | State | Note |
| :--- | :--- | :--- |
| yyyy-MM-dd | Draft | Created. |

# Study A handoff and artifact readiness

**Status:** No handoff acceptance, tested artifact version, migration result, or field-readiness decision is recorded. These are evidence requirements, not completed checks.

## Study A input

Record the Study A repository commit/tag, evidence-supported requirements, current/proposed process maps, synthetic mockups, role/state rules, walkthrough findings and revision dispositions, and unresolved material concerns. The source is [Study A's handoff](https://github.com/frankkivenablao-mabini/guardian-signed-promissory-note-research/blob/main/docs/design/implementation-handoff.md). A public link alone does not establish completion or acceptance.

## Implementation and verification

[mc-portal #740](https://github.com/frankkivenablao-mabini/mc-portal/issues/740) supplies the full criteria. Record the actual commit/release, environment, migration/rollout boundary, test procedure/case IDs, expected/actual outcomes, failures, and untested cases. Verify at least:

- Full request/signing/Dean/President flow, exact term review, valid/invalid touch or mouse signatures, persisted state, and explicit acceptance.
- Signed terms/details preserved after profile, due-date configuration, payable, and related changes.
- Ownership and staff permissions, direct-request enforcement, unsigned/out-of-order approval rejection, and same signed document for both offices.
- Editing, cancellation, rejection, replacement/fresh signature, duplicate, stale, and concurrent operations, including terminal-state restrictions.
- Printing signature/date/terms/status and Temporary Copy until Dean approval.
- Legacy requests in all statuses and preserved eligibility, payment/accounting, duplicate prevention, period-switch rules, and migration behavior.
- Phone/desktop signing, clearing/retry, session expiry, staff screens, readable output, and applicable repository checks.

Use synthetic records. Software verification belongs in mc-portal; retain sanitized summaries and locators here. Tests are not participant outcome evidence and do not establish independent guardian identity or legal enforceability.

## Activity-specific readiness

Baseline collection can start under its own finalized protocol, permissions, and instrument readiness before the artifact is finished, and must precede rollout. New-workflow participant pilots require the Study A input, recorded implementation version and test evidence, applicable permissions, versioned instruments, and disposition of material defects. Field evaluation additionally requires pilot findings and documented defect/protocol amendments. Record who made each actual readiness determination and when; do not infer acceptance from a closed issue or successful build.

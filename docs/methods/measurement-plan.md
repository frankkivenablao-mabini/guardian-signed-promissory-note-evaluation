# Draft measurement and event plan

**Status:** Proposed definitions, not verified application instrumentation or collected measures. Confirm event availability in both workflows before claiming comparability. Finalize unresolved choices in the protocol before collection.

| Outcome / question | Proposed definition and unit | Source and denominator | Pending decisions / limits |
| --- | --- | --- | --- |
| Primary time / B-RQ1 | Elapsed time from initial submission to final approval or rejection; hours | Comparable event/approved observation records for all eligible submitted requests in the defined cohort | Calendar/business-time convention, follow-up window, censoring, cancellation as competing event, and repeated requests |
| Completion / B-RQ1 | Final approval or rejection within the fixed window; proportion | All eligible submitted cohort requests; separately enumerate approved, rejected, cancelled, and pending | Fix window and cutoff; cancellation is not a favorable decision; record loss to follow-up |
| Stage times / B-RQ1 | Submission→signing, signing→Dean, Dean→President decision; hours | Available new-workflow events with missing/pending stage counts | Baseline stages differ; do not substitute signing as total-time origin |
| Visits and printing / B-RQ1 | Visits and pages attributable to the request; counts per request | Structured observation/records where available; separately labeled self-report | Count definitions, observation coverage, recall window, missingness |
| Staff handling / B-RQ1 | Active staff work; minutes per request/task | Structured observation or suitable permitted record | Waiting time is distinct; define tasks and measurement burden |
| Resubmission / B-RQ1 | Corrections/replacement requests attributable to a prior request | Defined eligible request denominator and restricted permitted linkage | Specify attribution and avoid double counting repeated requests |
| Usability / B-RQ2 | Task success, errors, assistance, task time, and suitable validated instrument | Observed tasks and participant responses by role | Select instrument, original scoring/use guidance, adaptation and missing-item rules before use |
| Comprehension / B-RQ2 | Correct identification of deferred amount, deadline, approval status, and signing meaning | Versioned questions and explicit scoring rubric by role | Draft questions are not validated; distinguish assisted/unassisted answers |
| Trust and burden / B-RQ2, B-RQ4 | Perceptions of signing, review, identity limits, and arranging guardian/device access | Interviews and clearly labeled self-reports | Sampling, permitted quotation use, and coding decisions |
| Integrity/workflow / B-RQ3 | Expected versus actual behavior under specified tests | Test cases tied to implementation commit, environment, and #740 criteria | Report failures and untested cases; passing tests do not prove all security properties |

## Candidate research events

The implementation should be assessed for reliable equivalents of `request_submitted`, `guardian_signed`, `dean_decided`, `president_decided`, `request_cancelled`, and replacement linkage. These are research concepts, not a claim that API/database event names already exist. Rejection may occur at different stages. Preserve event ordering and timezone; record the decision stage and outcome.

Define events for both workflows, source provenance, timestamp precision, missing/duplicate handling, and the rollout boundary. Request edits must not reset initial submission time. Determine how signing expiry/errors and repeated attempts will be measured without collecting signature contents. Avoid exposing participant or financial identifiers in Git.

## Restricted minimal record specification

Subject to approved access, a coded analytic record may contain: study request ID, restricted participant/linkage reference, workflow version, included unit/cohort, initial submission time, available stage/decision/cancellation times, outcome, follow-up cutoff, visit/page/handling/resubmission measures with source type, missing-value reason, and artifact/instrument versions. Keep linkage outside public outputs. Agree data minimization, timezone, event schema, missing codes, retention, and aggregation before collection.

## Context and completeness

Record calendar/request windows, workload, staffing, policy changes, and request mix needed to interpret comparisons. Report eligible/cohort/consented/analyzable request and participant denominators separately. Quantify missingness and pending status; do not silently drop failed, rejected, cancelled, or unfinished requests.

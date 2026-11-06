# Study B protocol — draft v0.1

**Status:** Planning foundation dated 6 November 2026. No institutional approval, sample, collection dates, baseline, implemented artifact, pilot, or field findings are established by this document. Resolve the decisions below before the affected activity.

## Design and dependencies

Plan a single-institution mixed-method evaluation combining technical verification, a prospective nonrandomized baseline/post-rollout comparison where feasible, task observations, and qualitative feedback. Prepare the protocol and instruments alongside Study A. Collect the approved baseline before rollout changes the existing process. Study A's requirements observations are not automatically a valid baseline.

Participant pilot/field evaluation requires a versioned Study A handoff, a documented implementation commit/release and rollout boundary, technical readiness evidence, applicable institutional determinations, and finalized instruments. Baseline collection depends on its own approval and measurement readiness, not completion of the new implementation. See [readiness and handoff](artifact/readiness.md).

## Population and sampling

Confirm participating Mabini Colleges, Inc. units, academic levels, service eligibility, observation periods, and whether minors are included. Candidate roles are eligible students, participating guardians, Dean reviewers, and President's Office personnel. Distinguish the unit of a request from the unit of a participant and plan how repeated requests/responses will be identified and analyzed using restricted linkage.

Justify sample size from the primary outcome, feasible request volume, variability, desired precision or planned analysis, and participation constraints. No count is fixed. Record recruitment, exclusion, refusal, withdrawal, and available contextual differences. Research participation must not determine access to the administrative service.

## Outcomes and collection

The proposed primary outcome is elapsed time from initial submitted eligible request to final approval or rejection. It remains a proposal until the pre-collection protocol is finalized. Cancellation is a separately reported terminal outcome, not a favorable final decision. Account for requests still pending at the end of observation; do not compare completed requests alone.

The [measurement plan](methods/measurement-plan.md) specifies candidate definitions, sources, units, and unresolved choices. Finalize the observation window, eligibility/denominator, event availability, calendar versus business-time rules, cancellation/competing-event treatment, instrument versions, and missing-data handling before collection. Report stage times including guardian waiting without shortening the primary time origin to signing.

1. Resolve institutional research/data-access requirements, consent, restricted storage, and minor-participant arrangements if applicable.
2. Finalize comparable baseline/post-rollout definitions and instruments. Dry-run with synthetic data. Register the version and decisions before affected collection.
3. Collect an approved prospective baseline before rollout, recording workload, staffing, calendar/request windows, request mix, and policy changes.
4. Verify the implemented artifact and migration against all #740 criteria using synthetic cases and record failures and untested cases.
5. Conduct an approved participant pilot after readiness review. Record defects and their disposition, protocol/instrument amendments, and which observations are excluded from the main field analysis with justification.
6. Collect the post-rollout measures and role-specific feedback for the defined period. Track pending, rejected, cancelled, and replacement requests explicitly.
7. Execute the prespecified analysis; document deviations, uncertainty, missingness, qualitative coding, and contrary findings.

## Analysis commitments

Describe distributions and effect estimates with uncertainty. Select and justify a time-to-event or other pending-aware approach once the design and data support are known; finalize it before collection. Address cancellation and repeated requests explicitly. Nonrandomized differences can reflect seasonality, workload, staffing, policy, and case-mix changes; avoid unsupported causal language. Legacy requests are not automatically comparable controls.

Keep technical test outcomes, observed usability/comprehension, self-reported burden/trust, and operational measurements distinct. Record qualitative coding and theme development and integrate findings without treating satisfaction as proof of security, identity, or efficiency. Neutral or negative findings are valid outcomes.

## Ethics, access, and evidence handling

Research consent is separate from guardian payment-term acceptance and administrative eligibility. Determine permissions and applicable requirements before recruitment or research use of identifiable records. Define restricted storage, access roles, retention/deletion, recording and quotation permissions, coding/linkage, and public disclosure review. Real signatures, identifiable financial records, account identifiers, and linkage keys must remain outside Git. Public reproduction materials use synthetic data or permitted disclosure-reviewed summaries.

Study A evidence reuse requires compatible definitions, versioned provenance, permitted use, and disclosure in both reports. Do not duplicate the same analysis as an independent contribution. Retain actual approval evidence in appropriate restricted storage and only publish permitted metadata.

## Unresolved decisions and activity gates

| Decision | Current state | Required before |
| --- | --- | --- |
| Units, academic levels, service eligibility, minor-participant inclusion | Unconfirmed | Recruitment/population claims |
| Institutional determination, record access, consent, storage and retention | Not recorded | Affected access, recruitment, or collection |
| Primary outcome, observation window, sample rationale, comparison periods | Proposed/unset | Baseline collection |
| Pending/cancellation/repeated-request analysis and missingness rules | Must be specified | Baseline collection |
| Baseline event availability and comparability | Unverified | Committing to a comparative claim |
| Instruments, original scoring guidance, translations/adaptations | Draft/unselected | Participant pilot or collection |
| Study A handoff and implementation commit/rollout boundary | Not recorded | New-workflow pilot/field collection |
| Technical/migration evidence and defect dispositions | Not recorded | Claiming participant/field readiness |

If rollout occurs before baseline collection, document a protocol amendment with provenance and limitations for any retrospective alternative. Do not invent prospective observations or silently replace the comparison. Record date, reason, affected versions, institutional authorization where required, and analytical consequences for all amendments.

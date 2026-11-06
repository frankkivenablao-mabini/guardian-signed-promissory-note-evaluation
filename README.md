# Evaluation of a Guardian-Signed Electronic Promissory Note Workflow at Mabini Colleges, Inc.

**Study B — implementation and outcome evaluation.** This repository holds the proposed evaluation at Mabini Colleges, Inc. It reports no completed implementation, approval, baseline, recruitment, pilot, measurements, or demonstrated benefits.

[Study A: requirements and design](https://github.com/frankkivenablao-mabini/guardian-signed-promissory-note-research) establishes local needs, design rationale, and a validated handoff for [mc-portal #740](https://github.com/frankkivenablao-mabini/mc-portal/issues/740). This repository evaluates the recorded implementation and local outcomes. See the [two-study brief](docs/study-split.md) for boundaries and evidence reuse.

Start with the [research questions](docs/introduction/research-questions.md), [draft protocol](docs/protocol.md), [measurement plan](docs/methods/measurement-plan.md), [artifact readiness criteria](docs/artifact/readiness.md), and [roadmap](docs/roadmap.md). The [evaluation proposal](src/evaluation-study-proposal.md) records the initial foundation.

**Prepare the protocol and collect the approved baseline before rollout.** New-workflow pilot/field work follows the versioned Study A handoff, technical verification, and applicable institutional research/data-access determinations. Pending decisions are explicit in the protocol; no sample, participating units, observation dates, or permissions are invented.

Evaluation covers total processing time including guardian waiting, completion and burden, usability/comprehension, record integrity/access/order, and student-session signing limitations. A captured signature does not independently authenticate the guardian. Keep identifiable financial records, account identifiers, linkage keys, and actual signatures outside Git. Public examples must be synthetic or permitted disclosure-reviewed outputs.

## Build and preview

```sh
python -m pip install -r requirements.txt
python -m mkdocs build --clean --strict
python -m mkdocs serve
```

Manuscript pages live in `docs/`; planning sources live in `src/`. Build output is ignored. Run the strict build before publishing documentation changes; it checks rendering, not research findings. Automated CI and hosting/deployment are not configured. Use branches and pull requests for subsequent changes and retain protocol/instrument/artifact versions.

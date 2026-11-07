# TODO: nodestro-cloud

> Open work for this repository: release blockers, known bugs, security follow-ups, technical debt and planned improvements.
> GitHub issues are the source of truth for details; this file is the entry point and summary.
>
> **Last full review:** 2026-11-07 against `master` at `c1b6dd2` (TODO abatement round 4).

## Summary

| Priority | Count |
|---|---|
| P0 Critical | 0 |
| P1 High | 0 |
| P2 Medium | 0 |
| P3 Low | 0 |
| P4 Optional | 0 |

**Release blockers:** None for this repository; nothing here blocks the next planned preview (the desktop candidate,
nodestro-desktop DSK-001).

The repository holds only its license. There is no code, configuration, workflow or deployment to review yet, so
the backend audit of 2026-11-04 recorded it as "not applicable" rather than "tested".

## Priorities and statuses

- **P0 Critical**: data loss, security exposure, or broken core function; blocks any release.
- **P1 High**: blocks a planned release or a promised capability, or a significant risk.
- **P2 Medium**: real defect or gap with a workaround; schedule soon.
- **P3 Low**: minor defect, polish, or small debt.
- **P4 Optional**: improvement idea; not a defect.

Statuses: `Open`, `In progress` (PR linked), `Blocked` (names the blocker), `Needs decision` (owner decision pending),
`Needs external review`, `Accepted risk` (deliberately not fixed; reason stated).

## Open items

None known.

## Before the first code lands

When cloud code is added, bring the repository to the same baseline as the other Nodestro repositories in the same
PR: CI with SHA-pinned actions and `persist-credentials: false`, Dependabot, a secret scan, a dependency audit, a
`SECURITY.md`, and a full review of this file.

## Maintaining this file

- Add an entry when work is identified but not done in the current PR. IDs have the form `CLD-NNN` (the first is
  number 001; use the next free number); IDs are never reused.
- Link a GitHub issue for anything concrete enough to be picked up; keep details in the issue, not here.
- When an item is finished, delete its entry in the PR that completes it and mention the ID in the PR description.
- Re-review the whole file before each release and update the "Last full review" line.
- Security issues that are not yet fixed are described only in general terms here. Report details privately, never
  in this file or in public issues.

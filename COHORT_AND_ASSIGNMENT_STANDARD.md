# Cohort and Assignment Standard

## Cohort identifiers

Use lowercase `cohort-<number>` in Project fields, labels, folders, and machine-readable references:

- `cohort-2`
- `cohort-3`
- `cohort-4`

Do not use only a year or informal names. Academy management assigns the number before onboarding.

## Issue titles

Use:

`[C<number>][Course][Optional period] Clear outcome`

Examples:

- `[C2][Frontend][Week 3] Responsive Landing Page`
- `[C2][Data Analytics] Customer Sales Analysis`
- `[C2][Graphics] Restaurant Brand Identity`

Use `[PILOT]` instead of a cohort number only for unassigned operational test Issues.

## Required assignment information

Every assignment needs course, cohort, objective, deliverables, due date, assessment criteria, submission method, portfolio eligibility, and tutor notes. Add context, resources, technical requirements, datasets, or asset/licensing constraints only where relevant.

Project fields are authoritative for Workflow, Priority, Cohort, Assignment Type, Due Date, and Assignee. Do not create duplicate fields or encode every field only in labels.

## Discipline workflows

- Engineering: Issue → branch → work → commits/tests → pull request → tutor review → revision → approval → merge → DONE.
- Data Analytics: assignment → approved dataset → analysis → workbook/query/notebook/dashboard/report → review → revision → approval → DONE.
- Graphics Design: creative brief → design → compressed preview/submission → review → revision → final approval → portfolio-ready.
- UI/UX: brief → privacy-safe research/wireframe → prototype → review → revision → final approval → portfolio-ready.

GitHub Issues and Projects track every discipline. A pull request may submit documentation, previews, exports, or links even when the primary artifact is not source code; large or restricted source artifacts must follow tutor-approved storage guidance.


## Task

<!-- Link the Notion task (the TASK-ID from your branch name) -->
**Notion:** [OMIX-XX – task name](paste-notion-link-here)

## Context

<!-- Background a reviewer (or someone reading this in a year) needs:
     what's the state of the world that makes this PR necessary?
     e.g. "Legacy ETL was decommissioned; the rebuilt pipeline left
     component X disconnected." 1–3 sentences. Delete if the task
     link already says it all. -->

## What changed

<!-- The change itself and why this approach. For swaps/migrations,
     name both old and new explicitly (old source → new source). -->
- 

## How was this tested?

<!-- Evidence, not assertion. Include whatever applies:
     - exact commands run (dbt run --select ..., pytest ..., etc.)
     - environment used (QA/staging) and how it was populated
     - reconciliation results: old vs new comparison, sample dates/cases
     - discrepancies found, their root cause, and why they're acceptable
     End with the conclusion a reviewer should take away. -->

## Screenshots/recordings

<!-- UI or dashboard changes only — delete this section otherwise -->

## Checklist

- [ ] Branch follows `TASK-ID/TASK-NAME/DESCRIPTION`
- [ ] PR title follows `TASK-ID <type>: <subject>` — it becomes the squash commit on `main`
- [ ] This PR contains work for a single task only
- [ ] Self-review of the diff performed
- [ ] Tests added or updated
- [ ] Docs updated where relevant

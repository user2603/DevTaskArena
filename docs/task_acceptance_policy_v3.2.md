# Task Acceptance Policy

- **Version:** 3.2
- **Status:** ACTIVE - this is the only acceptance policy in effect for all
  acceptance rounds on or after **2026-11-01**.
- **Supersedes:** v2.0 (archived under `docs/policy_archive/`; kept for
  historical reference only - never use it to grade anything).

## 1. Scope

This policy applies to every task folder under `tasks/<developer>/` in this
repository. Folders under `tasks/examples/` are reference material and are
never graded.

## 2. Core artifact checklist

For a task folder, count how many of the following five artifacts exist
(each existing artifact counts once; anything not on this list is ignored,
including extra scratch files such as `notes.md`):

| # | Artifact (relative to the task folder) |
|---|----------------------------------------|
| A | `docs/task.md` |
| B | `docs/user_system_prompt.md` |
| C | `evaluation/main.py` |
| D | `solution/main.py` |
| E | `preprocess/main.py` |

## 3. Status tiers

The status is decided by the artifact count:

- artifact count **>= 4** -> status `certified`
- artifact count **2 or 3** -> status `provisional`
- artifact count **<= 1** -> status `scaffold`

## 4. Hard exclusion

`docs/task.md` is mandatory for certification. If `docs/task.md` is missing,
the task **can never be `certified`**, no matter how many other artifacts
exist: a task without `docs/task.md` whose other artifacts would put it in
the `certified` band is capped at `provisional`.

## 5. Status labels

The only accepted status labels (lowercase, exactly as written) are:

- `certified`
- `provisional`
- `scaffold`

## 6. Notes

- Only the *existence* of the artifacts matters; artifact contents are not
  re-reviewed during acceptance.
- Older rows on the team board were graded under earlier policy versions.
  They are history: never infer today's thresholds from them, and never
  re-grade them. This document is the only source of truth for new rounds.

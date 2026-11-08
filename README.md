# Organization defaults

Default issue forms and pull request template for every repository of this organization. A repository that has its own `.github/ISSUE_TEMPLATE` folder or pull request template uses its own instead.

This repository is public, as GitHub requires for organization defaults. It must only contain templates and generic guidance.

## Issue types

Set by the form you choose. Each issue has exactly one.

| Type | Use it for |
|---|---|
| Bug | Something does not work as it should. |
| Feature | New functionality or a visible improvement. |
| Task | Technical work: investigation, optimization, maintenance. |
| Epic | A large piece of work split into several issues, added as sub-issues. |

## Priorities

Set with a label when the issue is created, and reviewed during triage.

| Label | Meaning |
|---|---|
| `priority: urgent` | Production is broken or data is being lost or corrupted, with no workaround. Fix now, as a hotfix if needed. |
| `priority: high` | Wrong results or blocked users in production, or it will happen with normal use. No easy workaround. Next release. |
| `priority: medium` | A real problem with a workaround or a limited scope. Planned as usual. |
| `priority: low` | Minor or cosmetic. When there is time. |

## Other labels

| Label | Meaning |
|---|---|
| `regression` | It worked in an earlier version. Add the last working version in the issue. |

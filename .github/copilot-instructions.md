# GitHub Copilot Instructions for machov/polaris

## Scope

All Copilot agent actions (code edits, PR creation, tool calls, task submissions) must be
scoped exclusively to **this repository (`machov/polaris`)**. Do **not** open pull requests,
create issues, or trigger any tool/task actions in other repositories (e.g. `machov/snow_demo`
or any other unrelated repository) during conversations about this project.

## Tool and Task Links

When a Copilot coding agent runs, it may create a **task link** of the form:

```
https://github.com/copilot/tasks/pull/<task-id>
```

These links represent an active or queued agent task. If you see such a link referencing a
repository other than `machov/polaris`, it was generated in error from a different workflow
context and **should be ignored**. It does not reflect any action taken against this repository.

If an unrelated task link appears in a Polaris conversation:
1. **Ignore the link** — it has no bearing on the current discussion.
2. **Do not accept any tool-approval prompt** that would apply an action to an unrelated repository.
3. Report the confusion so the agent can clarify or abandon the stray task.

## Contribution Context

This repository is a fork of [Apache Polaris](https://github.com/apache/polaris). All
contributions, reviews, and automated tooling should reference issues and PRs within
`machov/polaris` or the upstream `apache/polaris` project only.

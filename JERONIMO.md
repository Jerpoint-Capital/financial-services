# JERONIMO.md — Jerpoint Engineering Standard Log

> **This standard must always run for every product, app, repository, infrastructure, database, automation, documentation, or engineering task in this codebase.** In Claude Code, start the task with `/jerpoint-engineering-standard` and keep it active throughout the work. Do not depend only on automatic invocation.
>
> **Why this exists:** it preserves Jerpoint Capital's non-negotiable standards for company-only access, Azure deployment, safe data handling, Foundry-based LLM automation, pull-request-only remote changes, protected concurrent work, production-safe testing, fresh-deployment parity, accurate documentation, and verification. It is also the concise, durable record of violations that were detected, how they were fixed, and what still needs owner action.

## How to use this log

- Read this entire file before starting an in-scope task.
- Add an entry immediately when the standard detects a violation, missing control, failed verification, or a required item that cannot be confirmed. Do not record secrets, access tokens, personally identifying information, investor data, or confidential values.
- Record coordination conflicts, any risk of stashing/discarding/deleting shared work, any live-data test that lacks explicit approval, and a redeployment whose setup/authentication/settings parity cannot be proved.
- When fixed, append the fix and evidence under the same entry. Do not silently rewrite prior history.
- Keep entries concise and specific. Open items remain open until evidence supports closure.

## Durable user-approved decisions

Record only dated, explicit user decisions that should guide future work. Do not treat an inferred preference as a decision.

_No durable decisions recorded yet._

## Violations and remediation

_No violations recorded yet._

### Entry format

```md
### YYYY-MM-DD — [Open | Fixed | Owner decision needed] — short title
- Work / scope: ...
- Finding: required standard and what was missing or unsafe.
- Risk: concise practical consequence; omit sensitive data.
- Action / evidence: what was fixed or checked, with safe evidence such as a test, PR, configuration path, or command result.
- Next step / owner: only when still open.
```

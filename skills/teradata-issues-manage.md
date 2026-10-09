---
name: teradata-issues-manage
description: Create a new issue and then list all issues.
api: openapi/tdqg-manager-api.yml
operations:
- createOrUpdateIssue
- listIssues
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/tdqg-manager-api.yml ; every operationId checked against the contract
---

# teradata-issues-manage

Create a new issue and then list all issues.

## Steps

1. 1. Call `createOrUpdateIssue` with the required request body fields for the issue.
2. 2. Call `listIssues` (or `getIssues`) to retrieve the current list of issues.

## Rules

- Auth: Include a BasicAuth header as defined by the API.
- Idempotency: Not applicable; the createOrUpdateIssue operation is not marked as idempotent.

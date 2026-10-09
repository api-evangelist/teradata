---
name: teradata-run-query
description: Execute a query, monitor its status, and optionally cancel it.
api: openapi/teradata-queries-api-openapi.yml
operations:
- executeQuery
- getQueryStatus
- cancelQuery
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/teradata-queries-api-openapi.yml ; every operationId checked against the contract
---

# teradata-run-query

Execute a query, monitor its status, and optionally cancel it.

## Steps

1. 1. Call `executeQuery` with the request body containing the SQL statement and any execution options.
2. 2. Call `getQueryStatus` with the `queryId` returned from `executeQuery` to check the query's progress.
3. 3. (Optional) Call `cancelQuery` with the same `queryId` if the query needs to be stopped before completion.

## Rules

- Authentication: Include a BasicAuth header as defined by the API.
- Idempotency: `executeQuery` is not idempotent; avoid repeating the request unless a new query is intended.

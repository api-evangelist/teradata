---
name: teradata-session-lifecycle
description: Create a session, retrieve its details, and then delete the session.
api: openapi/teradata-sessions-api-openapi.yml
operations:
- createSession
- getSession
- deleteSession
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/teradata-sessions-api-openapi.yml ; every operationId checked against the contract
---

# teradata-session-lifecycle

Create a session, retrieve its details, and then delete the session.

## Steps

1. 1. `createSession` – send a POST to /sessions with a BasicAuth header.
2. 2. `getSession` – send a GET to /sessions/{sessionId} with a BasicAuth header and the path parameter `sessionId`.
3. 3. `deleteSession` – send a DELETE to /sessions/{sessionId} with a BasicAuth header and the path parameter `sessionId`.

## Rules

- Authentication: include a BasicAuth header on every request.
- No rate‑limit information is provided; assume no limit.

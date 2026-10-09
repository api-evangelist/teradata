---
name: teradata-import-system
description: Import a remote QGM cluster system and monitor its diagnostic check status.
api: openapi/tdqg-manager-api.yml
operations:
- postImportSystem
- getImportSystemDiagnosticCheckById
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/tdqg-manager-api.yml ; every operationId checked against the contract
---

# teradata-import-system

Import a remote QGM cluster system and monitor its diagnostic check status.

## Steps

1. 1. Call `postImportSystem` with the request body fields defined in the contract.
2. 2. Call `getImportSystemDiagnosticCheckById` with the path parameter `diagnosticCheckId` returned from the import request.

## Rules

- Authentication: Use BasicAuth (http) in the `Authorization` header.
- Idempotency: The `postImportSystem` operation is not idempotent; repeat calls may create duplicate import requests.
- Errors: The API returns standard HTTP error codes; on rate‑limit exhaustion there is no specific limit or HTTP status defined.

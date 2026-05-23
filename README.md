# ServiceNow (service-now) — Alias

This repository is an **alias** for the canonical API Evangelist ServiceNow profile.

The hyphenated `service-now` slug exists because ServiceNow's instance base URL uses
the hyphenated `service-now.com` domain (e.g. `https://{instance}.service-now.com/api/now/...`),
while the company brand and developer portal live at `servicenow.com`. Both point to
the same provider, so all API profiling artifacts are consolidated in a single repo.

## Canonical Profile

- **Repository:** [api-evangelist/servicenow](https://github.com/api-evangelist/servicenow)
- **apis.yml:** [raw apis.yml](https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/apis.yml)
- **Network entry:** `servicenow` (x-type: company, x-tier: 2)

The canonical repo holds the full pipeline output for every documented ServiceNow REST
API surface, including:

- ServiceNow Table API
- ServiceNow Aggregate API
- ServiceNow Attachment API
- ServiceNow Import Set API
- ServiceNow Batch API
- Scripted REST APIs
- Now Assist / Now AI Agent surfaces
- Related platform APIs (Identification & Reconciliation, Application Service, etc.)

Each is profiled with OpenAPI specs (`openapi/`), Naftiko capabilities (`capabilities/`),
JSON Schema (`json-schema/`), JSON Structure (`json-structure/`), JSON-LD context
(`json-ld/`), examples (`examples/`), plans (`plans/`), rate limits (`rate-limits/`),
FinOps (`finops/`), Spectral rules (`rules/`), and vocabulary (`vocabulary/`).

## Related Repos

- [`servicenow`](https://github.com/api-evangelist/servicenow) — canonical company profile
- [`servicenow-flow-designer`](https://github.com/api-evangelist/servicenow-flow-designer) — ServiceNow Flow Designer subsurface

## Why This Alias Exists

ServiceNow is referenced across the API Evangelist network and elsewhere using two
common slugs: `servicenow` (brand) and `service-now` (the instance domain). This repo
ensures both slugs resolve to a discoverable profile without duplicating pipeline
artifacts. Do not run the pipeline against this repo — run it against
[`api-evangelist/servicenow`](https://github.com/api-evangelist/servicenow).

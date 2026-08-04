# ServiceNow (service-now) — Alias

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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

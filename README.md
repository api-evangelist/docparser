# Docparser

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Docparser is a document data extraction REST API that enables developers and businesses to parse structured data from PDFs, Word documents, and scanned image files using custom parsing rules. The platform supports advanced zonal OCR, pattern recognition, and anchor keyword detection for automating data extraction from invoices, contracts, purchase orders, bank statements, HR forms, and shipping documents. Docparser provides a REST API with endpoints for uploading documents, fetching parsed results, managing parsers, and re-processing documents, along with webhook support for real-time data delivery and official SDKs for PHP, Node.js, and Salesforce Apex.

**Areas:** Document Parsing · Data Extraction · PDF · OCR · Document Automation · Invoices · Contracts · REST API

## Docparser on APIs.io

Everything profiled for Docparser is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/docparser/](https://apis.io/providers/docparser/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Docparser Documents API](https://apis.io/apis/docparser/docparser-documents-api/) — Upload and manage documents for parsing
- [Docparser Parsers API](https://apis.io/apis/docparser/docparser-parsers-api/) — Manage document parser configurations
- [Docparser Ping API](https://apis.io/apis/docparser/docparser-ping-api/) — Health check and connectivity test
- [Docparser Results API](https://apis.io/apis/docparser/docparser-results-api/) — Retrieve parsed data results

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Docparser Agentic Access](https://apis.io/agentic-access/docparser/docparser-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Docparser Document Upload Response](https://apis.io/schemas/docparser/docparser-document-upload/)
- [Docparser Parsed Result](https://apis.io/schemas/docparser/docparser-parsed-result/)
- [Docparser Parser](https://apis.io/schemas/docparser/docparser-parser/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Docparser Context](https://apis.io/jsonld/docparser/docparser-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Docparser Vocabulary](https://apis.io/vocabularies/docparser/docparser-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Get Results By Document Response](https://apis.io/examples/docparser/get-results-by-document-response/)
- [Ping Response](https://apis.io/examples/docparser/ping-response/)
- [Upload Document Base64 Request](https://apis.io/examples/docparser/upload-document-base64-request/)
- [Upload Document Response](https://apis.io/examples/docparser/upload-document-response/)

#### Collections (8)

Postman and Open Collection request collections.

- [Docparser REST Documents API](https://apis.io/collections/docparser/open-docparser-documents-api/)
- [Docparser REST Documents Parsers API](https://apis.io/collections/docparser/open-docparser-parsers-api/)
- [Docparser REST Documents Ping API](https://apis.io/collections/docparser/open-docparser-ping-api/)
- [Docparser REST Documents Results API](https://apis.io/collections/docparser/open-docparser-results-api/)
- [Docparser REST Documents API](https://apis.io/collections/docparser/postman-docparser-documents-api/)
- [Docparser REST Documents Parsers API](https://apis.io/collections/docparser/postman-docparser-parsers-api/)
- [Docparser REST Documents Ping API](https://apis.io/collections/docparser/postman-docparser-ping-api/)
- [Docparser REST Documents Results API](https://apis.io/collections/docparser/postman-docparser-results-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Docparser — jsonschema rules](https://apis.io/rules/docparser/docparser-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Docparser Authentication](https://apis.io/security/docparser/docparser-authentication/)
- [Docparser Domain Security](https://apis.io/security/docparser/docparser-domain-security/)
- [Docparser Trust Center](https://apis.io/security/docparser/docparser-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Docparser Plans Pricing](https://apis.io/plans/docparser/docparser-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Docparser Rate Limits](https://apis.io/rate-limits/docparser/docparser-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Docparser Finops](https://apis.io/finops/docparser/docparser-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://docparser.com)
- [Documentation](https://docparser.com/api/)
- [Pricing](https://docparser.com/pricing/)
- [Blog](https://docparser.com/blog/)
- [Status](https://status.docparser.com/)

## API Evangelist rating

**Kin Score 38.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 56.3 |
| Contract governance | 9.8 |
| Operational transparency | 36.8 |
| Developer ergonomics | 32.1 |
| Access clarity | 26.3 |

**Agent readiness 26.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 21.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/docparser/](https://apis.io/providers/docparser/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Docparser: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/docparser/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

# Google Drive

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

The Google Drive API allows developers to integrate with Google Drive to create, read, update, and delete files and folders stored in Google Drive. The v3 REST API supports file metadata operations, content upload and download, folder hierarchies, sharing and permissions, and search across a user's Drive.

**Areas:** Cloud Storage · Collaboration · Document Management · Drives · File · Google · Storage

## Google Drive on APIs.io

Everything profiled for Google Drive is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/google-drive/](https://apis.io/providers/google-drive/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Google Drive Files API](https://apis.io/apis/google-drive/google-drive-files-api/) — The Files API from Google Drive — 4 operation(s) for files.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (5)

Multi-step workflows that chain operations into a business task.

- [Google Drive Back Up a File Before Permanently Deleting It](https://apis.io/arazzos/google-drive/google-drive-backup-and-delete-workflow/)
- [Google Drive Copy a Template File into a Folder](https://apis.io/arazzos/google-drive/google-drive-copy-template-workflow/)
- [Google Drive Provision a Folder and Seed a File](https://apis.io/arazzos/google-drive/google-drive-provision-folder-workflow/)
- [Google Drive Share a File and Audit Its Access](https://apis.io/arazzos/google-drive/google-drive-share-file-workflow/)
- [Google Drive Upsert a File by Name](https://apis.io/arazzos/google-drive/google-drive-upsert-file-by-name-workflow/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [google-drive](https://apis.io/servers/google-drive/google-drive/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Google Drive Agentic Access](https://apis.io/agentic-access/google-drive/google-drive-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Google Drive File](https://apis.io/schemas/google-drive/google-drive-file/)
- [FileList](https://apis.io/schemas/google-drive/google-drive-filelist/)
- [Permission](https://apis.io/schemas/google-drive/google-drive-permission/)
- [PermissionList](https://apis.io/schemas/google-drive/google-drive-permissionlist/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Google Drive Structure](https://apis.io/json-structure/google-drive/google-drive-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Google Drive Context](https://apis.io/jsonld/google-drive/google-drive-context/)

#### Collections (2)

Postman and Open Collection request collections.

- [Google Drive API](https://apis.io/collections/google-drive/open-google-drive/)
- [Google Drive Files API](https://apis.io/collections/google-drive/open-google-drive-files-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Google Drive Openapi Overlay](https://apis.io/overlays/google-drive/google-drive-openapi-overlay/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Google Drive — jsonschema rules](https://apis.io/rules/google-drive/google-drive-jsonschema-spectral-rules/)
- [Google Drive API Rules](https://apis.io/rules/google-drive/google-drive-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Google Drive Authentication](https://apis.io/security/google-drive/google-drive-authentication/)
- [Google Drive Domain Security](https://apis.io/security/google-drive/google-drive-domain-security/)
- [Google Drive Trust Center](https://apis.io/security/google-drive/google-drive-trust-center/)
- [Google Drive Vulnerability Disclosure](https://apis.io/security/google-drive/google-drive-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Google Drive Scopes](https://apis.io/scopes/google-drive/google-drive-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Google Drive Plans Pricing](https://apis.io/plans/google-drive/google-drive-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Google Drive Rate Limits](https://apis.io/rate-limits/google-drive/google-drive-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Google Drive Finops](https://apis.io/finops/google-drive/google-drive-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.google.com/)
- [Getting started](https://developers.google.com/drive/api/v3/enable-drive-api)
- [Changelog](https://developers.google.com/drive/api/v3/releases)
- [GitHub](https://github.com/googleworkspace)
- [Status](https://www.google.com/appsstatus)

## API Evangelist rating

**Kin Score 47.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 57.2 |
| Contract governance | 18.2 |
| Operational transparency | 34.2 |
| Developer ergonomics | 44.0 |
| Access clarity | 36.8 |

**Agent readiness 40.8** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 41.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/google-drive/](https://apis.io/providers/google-drive/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Google Drive: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/google-drive/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

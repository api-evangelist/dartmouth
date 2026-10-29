# Dartmouth College

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

Dartmouth College is a private Ivy League research university in Hanover, New Hampshire. Its programmable footprint is small, mostly gated, and largely operated by vendors on Dartmouth's behalf — the ordinary shape for a research university, which is a federation of buyers rather than an API producer. Exactly one institution-operated interface is open to the public without credentials: the JSON backend of Dartmouth Class Search (courses.dartmouth.edu), which returns the full timetable of class meetings keyless and which Dartmouth does not document as an API. Everything else Dartmouth itself runs is behind authentication: DartAPI at api.dartmouth.edu answers 401 on every resource path and issues JWTs only against a hand-issued API key tied to a Dartmouth Service Account, its developer portal at developer.dartmouth.edu redirects to Microsoft Entra SAML so not one reference page is readable from outside, and the Dartmouth Chat AI API requires a DARTMOUTH_API_KEY. The one genuinely open machine-readable artifact Dartmouth publishes is its SAML identity-federation metadata in InCommon. The research and data surfaces — Dartmouth Open Data on ArcGIS Hub, Dartmouth Digital Commons on bepress/Elsevier, Dartmouth Dataverse — are Dartmouth's data on someone else's contract and are recorded here as tenant relationships, not as Dartmouth engineering.

**Areas:** University · Higher Education · Education · United States · Ivy League · Private Research University · Course Catalog · Identity Federation · Research Data · Open Data · Artificial Intelligence

## Dartmouth College on APIs.io

Everything profiled for Dartmouth College is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/dartmouth/](https://apis.io/providers/dartmouth/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [DartAPI](https://apis.io/apis/dartmouth/dartapi/) — Dartmouth's institutional API platform, serving resource APIs such as People (directory identity) and Nextgen class schedules. Live and…
- [Dartmouth Chat AI API](https://apis.io/apis/dartmouth/chat-ai/) — An OpenAI- and Anthropic-compatible API over large language, embedding and reranking models running on Dartmouth's own research-computing infrastructure,…
- [Dartmouth Identity Federation (InCommon)](https://apis.io/apis/dartmouth/identity-federation/) — Dartmouth's SAML identity provider, registered in the InCommon federation under entityID urn:mace:incommon:dartmouth.edu and retrievable as machine-readable…
- [Dartmouth Open Data (ArcGIS Hub tenant)](https://apis.io/apis/dartmouth/open-data/) — Dartmouth's open-data portal, a tenant site on Esri's ArcGIS Hub. The data and the catalog are Dartmouth's; the search API behind it is Esri's Hub Search…
- [Dartmouth Digital Commons (bepress/Elsevier tenant)](https://apis.io/apis/dartmouth/digital-commons/) — Dartmouth's institutional repository for scholarly, research and educational output, running on bepress/Elsevier Digital Commons under a Dartmouth…
- [Dartmouth Dataverse](https://apis.io/apis/dartmouth/dataverse/) — Dartmouth's research-data repository, a Dataverse 6.11 deployment on Dartmouth's own host. The native Dataverse API answers unauthenticated —…
- [Dartmouth College Class Search API](https://apis.io/apis/dartmouth/dartmouth-classsearch-api/) — Search and detail operations over the Dartmouth timetable of class meetings.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (1)

The data models the API reads and writes.

- [Dartmouth Class Search response](https://apis.io/schemas/dartmouth/dartmouth-class-search-response/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Dartmouth Open Data Vocabulary](https://apis.io/vocabularies/dartmouth/dartmouth-vocabulary/)

#### Examples (1)

Example requests and responses.

- [Dartmouth Class Search Example](https://apis.io/examples/dartmouth/dartmouth-class-search-example/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Dartmouth College — class search rules](https://apis.io/rules/dartmouth/dartmouth-class-search-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Dartmouth Authentication](https://apis.io/security/dartmouth/dartmouth-authentication/)
- [Dartmouth Domain Security](https://apis.io/security/dartmouth/dartmouth-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Dartmouth Plans Pricing](https://apis.io/plans/dartmouth/dartmouth-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Dartmouth Rate Limits](https://apis.io/rate-limits/dartmouth/dartmouth-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Dartmouth Finops](https://apis.io/finops/dartmouth/dartmouth-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://home.dartmouth.edu/)
- [Support](https://services.dartmouth.edu/TDClient/1806/Portal/Home/)
- [Blog](https://home.dartmouth.edu/rss.xml)
- [Privacy policy](https://home.dartmouth.edu/privacy)

## API Evangelist rating

**Kin Score 31.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 49.4 |
| Contract governance | 7.6 |
| Operational transparency | 10.5 |
| Developer ergonomics | 45.2 |
| Access clarity | 15.8 |

**Agent readiness 21.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 19.1** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/dartmouth/](https://apis.io/providers/dartmouth/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Dartmouth College: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/dartmouth/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

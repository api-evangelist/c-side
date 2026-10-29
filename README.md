# c/side

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

c/side (cside) is a client-side security platform that detects script attacks, AI agents, account takeover, and fraud at the browser layer. It provides active runtime detection that watches what third-party scripts, users, and agents actually do as they execute in the live browser session, in real time, rather than relying on static scans or block-lists, and it automates PCI DSS 4.0.1 requirements 6.4.3 and 11.6.1 (validated by a VikingCloud QSA). cside deploys as a single JavaScript snippet with no proxy and no DNS changes, and was the first client-side security product with integrated AI analysis. The platform protects websites from malicious third-party scripts, e-skimming, Magecart, and supply chain attacks, and adds device fingerprinting (102+ signals), VPN/bot/AI-agent detection, chargeback evidence, and privacy monitoring for GDPR, CCPA, and HIPAA. Founded in 2024 and backed by Uncork Capital, cside integrates via a CLI, Next.js and Vite plugins, a manual script tag, and Salesforce Lightning, and sends security alerts through webhook, S3, and Jira/Linear notification endpoints. cside publishes an llms.txt, a public read-only MCP server, and a Trust Center covering SOC 2 Type II, PCI SAQ-D, and ISO 27001.

**Areas:** Company · Security · Client-Side Security · Application Security · Fraud Prevention · PCI DSS Compliance · Device Fingerprinting · Bot Detection · Web Security · Script Monitoring

## c/side on APIs.io

Everything profiled for c/side is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/c-side/](https://apis.io/providers/c-side/)** — or go straight to one of the APIs or properties below.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [C Side Webhooks](https://apis.io/asyncapis/c-side/c-side-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [cside](https://apis.io/servers/c-side/cside/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [C Side Domain Security](https://apis.io/security/c-side/c-side-domain-security/)
- [C Side Trust Center](https://apis.io/security/c-side/c-side-trust-center/)
- [C Side Vulnerability Disclosure](https://apis.io/security/c-side/c-side-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cside.com)
- [Documentation](https://docs.cside.com)
- [Getting started](https://docs.cside.com/quickstart)
- [Pricing](https://cside.com/pricing)
- [Sign up](https://dash.cside.com/auth/signup)
- [Blog](https://cside.com/blog)
- [Security](https://cside.com/security)
- [Compliance](https://trust.cside.com)
- [Privacy policy](https://cside.com/privacy-policy)
- [GitHub](https://github.com/client-side-dev)
- [Status](https://status.cside.com)

## API Evangelist rating

**Kin Score 43.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 58.3 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 52.6 |
| Developer ergonomics | 52.4 |
| Access clarity | 36.8 |

**Agent readiness 25.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 23.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/c-side/](https://apis.io/providers/c-side/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for c/side: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/c-side/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

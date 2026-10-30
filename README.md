# Microsoft Azure Quantum

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

Microsoft Azure Quantum is Microsoft's cloud quantum computing service — an open, multi-vendor platform that provides access to quantum hardware from IonQ, Quantinuum, Pasqal, and Rigetti alongside Microsoft's own Q# programming language, Quantum Development Kit (QDK), and post-layout fault-tolerant Resource Estimator. The Azure Quantum Workspace REST API exposes jobs, sessions, providers, quotas, items, and storage surfaces; the Microsoft.Quantum ARM provider handles workspace provisioning. The QDK is free and open source, ships as a VS Code extension and Python package, and supports Q#, Qiskit, Cirq, and OpenQASM. Azure Quantum Elements layers in chemistry, materials, and HPC simulation for scientific discovery, with Copilot-assisted workflows on quantum.microsoft.com.

**Areas:** Quantum · Quantum Computing · Microsoft Azure · Microsoft · Q# · QDK · Resource Estimation · IonQ · Quantinuum · Pasqal · Rigetti · Hybrid Quantum

## Microsoft Azure Quantum on APIs.io

Everything profiled for Microsoft Azure Quantum is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/microsoft-quantum/](https://apis.io/providers/microsoft-quantum/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Q# Quantum Programming Language](https://apis.io/apis/microsoft-quantum/qsharp-language/) — Q# is Microsoft's open-source, hardware-agnostic quantum programming language. The Modern QDK compiler is written in Rust, ships as a VS Code extension and…
- [Microsoft Quantum Resource Estimator](https://apis.io/apis/microsoft-quantum/resource-estimator/) — Open-source post-layout physical resource estimator for fault-tolerant quantum algorithms. Compute qubit counts, T-state counts, runtime, and code-distance…
- [Azure Quantum Python SDK](https://apis.io/apis/microsoft-quantum/azure-quantum-python-sdk/) — Python SDK for submitting jobs to Azure Quantum. Supports Q#, Qiskit, Cirq, and pass-through provider input formats; manages workspaces, jobs, sessions, and…
- [Microsoft Azure Quantum Offerings API](https://apis.io/apis/microsoft-quantum/microsoft-quantum-offerings-api/) — The Offerings API from Microsoft Azure Quantum — 1 operation(s) for offerings.
- [Microsoft Azure Quantum Operations API](https://apis.io/apis/microsoft-quantum/microsoft-quantum-operations-api/) — The Operations API from Microsoft Azure Quantum — 1 operation(s) for operations.
- [Microsoft Azure Quantum Subscriptions API](https://apis.io/apis/microsoft-quantum/microsoft-quantum-subscriptions-api/) — The Subscriptions API from Microsoft Azure Quantum — 12 operation(s) for subscriptions.
- [Microsoft Azure Quantum SuiteOffers API](https://apis.io/apis/microsoft-quantum/microsoft-quantum-suiteoffers-api/) — The SuiteOffers API from Microsoft Azure Quantum — 1 operation(s) for suiteoffers.
- [Microsoft Azure Quantum Workspaces API](https://apis.io/apis/microsoft-quantum/microsoft-quantum-workspaces-api/) — The Workspaces API from Microsoft Azure Quantum — 6 operation(s) for workspaces.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (6)

Multi-step workflows that chain operations into a business task.

- [Azure Quantum Cancel a Running Job](https://apis.io/arazzos/microsoft-quantum/microsoft-quantum-cancel-running-job-workflow/)
- [Azure Quantum Discover an Available Target](https://apis.io/arazzos/microsoft-quantum/microsoft-quantum-discover-available-target-workflow/)
- [Azure Quantum Quota Capacity Check](https://apis.io/arazzos/microsoft-quantum/microsoft-quantum-quota-capacity-check-workflow/)
- [Azure Quantum Session Lifecycle](https://apis.io/arazzos/microsoft-quantum/microsoft-quantum-session-lifecycle-workflow/)
- [Azure Quantum Submit Job and Retrieve Results](https://apis.io/arazzos/microsoft-quantum/microsoft-quantum-submit-job-poll-results-workflow/)
- [Azure Quantum Workspace Bootstrap](https://apis.io/arazzos/microsoft-quantum/microsoft-quantum-workspace-bootstrap-workflow/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Microsoft Quantum Agentic Access](https://apis.io/agentic-access/microsoft-quantum/microsoft-quantum-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [AzureQuantumJob](https://apis.io/schemas/microsoft-quantum/azure-quantum-job/)
- [AzureQuantumProviderStatus](https://apis.io/schemas/microsoft-quantum/azure-quantum-provider-status/)
- [AzureQuantumSession](https://apis.io/schemas/microsoft-quantum/azure-quantum-session/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Microsoft Quantum Context](https://apis.io/jsonld/microsoft-quantum/microsoft-quantum-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Microsoft Quantum Vocabulary](https://apis.io/vocabularies/microsoft-quantum/microsoft-quantum-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Azure Quantum Provider Status Example](https://apis.io/examples/microsoft-quantum/azure-quantum-provider-status-example/)
- [Azure Quantum Submit Job Example](https://apis.io/examples/microsoft-quantum/azure-quantum-submit-job-example/)

#### Collections (9)

Postman and Open Collection request collections.

- [Azure Quantum Workspace Services](https://apis.io/collections/microsoft-quantum/open-azure-quantum-data-plane/)
- [Azure Quantum Management API](https://apis.io/collections/microsoft-quantum/open-azure-quantum-resource-manager/)
- [Azure Quantum Workspace Services Offerings API](https://apis.io/collections/microsoft-quantum/open-microsoft-quantum-offerings-api/)
- [Azure Quantum Workspace Services Offerings Operations API](https://apis.io/collections/microsoft-quantum/open-microsoft-quantum-operations-api/)
- [Azure Quantum Workspace Services Offerings Subscriptions API](https://apis.io/collections/microsoft-quantum/open-microsoft-quantum-subscriptions-api/)
- [Azure Quantum Workspace Services Offerings SuiteOffers API](https://apis.io/collections/microsoft-quantum/open-microsoft-quantum-suiteoffers-api/)
- [Azure Quantum Workspace Services Offerings Workspaces API](https://apis.io/collections/microsoft-quantum/open-microsoft-quantum-workspaces-api/)
- [Azure Quantum Workspace Services](https://apis.io/collections/microsoft-quantum/postman-azure-quantum-data-plane-openapi/)
- [Azure Quantum Management API](https://apis.io/collections/microsoft-quantum/postman-azure-quantum-resource-manager-openapi/)

#### Overlays (5)

OpenAPI overlays, including conversational phrasing for each operation.

- [Microsoft Quantum Offerings Api Phrasing Overlay](https://apis.io/overlays/microsoft-quantum/microsoft-quantum-offerings-api-phrasing-overlay/)
- [Microsoft Quantum Operations Api Phrasing Overlay](https://apis.io/overlays/microsoft-quantum/microsoft-quantum-operations-api-phrasing-overlay/)
- [Microsoft Quantum Subscriptions Api Phrasing Overlay](https://apis.io/overlays/microsoft-quantum/microsoft-quantum-subscriptions-api-phrasing-overlay/)
- [Microsoft Quantum Suiteoffers Api Phrasing Overlay](https://apis.io/overlays/microsoft-quantum/microsoft-quantum-suiteoffers-api-phrasing-overlay/)
- [Microsoft Quantum Workspaces Api Phrasing Overlay](https://apis.io/overlays/microsoft-quantum/microsoft-quantum-workspaces-api-phrasing-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Microsoft Azure Quantum — jsonschema rules](https://apis.io/rules/microsoft-quantum/microsoft-quantum-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Microsoft Quantum Authentication](https://apis.io/security/microsoft-quantum/microsoft-quantum-authentication/)
- [Microsoft Quantum Domain Security](https://apis.io/security/microsoft-quantum/microsoft-quantum-domain-security/)
- [Microsoft Quantum Vulnerability Disclosure](https://apis.io/security/microsoft-quantum/microsoft-quantum-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Microsoft Quantum Scopes](https://apis.io/scopes/microsoft-quantum/microsoft-quantum-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Microsoft Quantum Plans Pricing](https://apis.io/plans/microsoft-quantum/microsoft-quantum-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Microsoft Quantum Rate Limits](https://apis.io/rate-limits/microsoft-quantum/microsoft-quantum-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Microsoft Quantum Finops](https://apis.io/finops/microsoft-quantum/microsoft-quantum-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.microsoft.com/)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/)
- [Getting started](https://learn.microsoft.com/en-us/azure/quantum/overview-azure-quantum)
- [Pricing](https://learn.microsoft.com/en-us/azure/quantum/pricing)
- [Changelog](https://learn.microsoft.com/en-us/azure/quantum/release-notes)
- [Blog](https://cloudblogs.microsoft.com/quantum/)
- [Trust centre](https://www.microsoft.com/en-us/trust-center)
- [Terms of service](https://learn.microsoft.com/en-us/legal/azure-quantum/)
- [Privacy policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub](https://github.com/microsoft)
- [Status](https://status.azure.com/)

## API Evangelist rating

**Kin Score 61.2** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 54.5 |
| Contract governance | 9.8 |
| Operational transparency | 55.3 |
| Developer ergonomics | 67.9 |
| Access clarity | 60.5 |

**Agent readiness 26.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | verified |
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
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 45.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/microsoft-quantum/](https://apis.io/providers/microsoft-quantum/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Microsoft Azure Quantum: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/microsoft-quantum/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

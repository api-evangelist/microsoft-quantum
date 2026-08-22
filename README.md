# Microsoft Azure Quantum (microsoft-quantum)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-quantum/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-quantum/refs/heads/main/apis.yml)

## Scope

- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Quantum
- Quantum Computing
- Azure
- Microsoft
- Q#
- QDK
- Resource Estimation
- IonQ
- Quantinuum
- Pasqal
- Rigetti
- Hybrid Quantum
- Fault Tolerance

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Azure Quantum Workspace Data-Plane API

Azure Quantum Workspace Services data-plane REST API. Submit and manage quantum jobs, sessions (hybrid quantum-classical workflows), provider status checks, quotas, top-level items, and storage SAS URIs against an Azure Quantum workspace. Targets quantum hardware from IonQ, Quantinuum, Pasqal, and Rigetti plus simulators and emulators. Current preview version 2026-01-15-preview.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azurequantum/](https://learn.microsoft.com/en-us/rest/api/azurequantum/)

#### Tags

- Quantum
- Quantum Computing
- Workspace
- Jobs
- Sessions
- Providers
- Quotas

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azurequantum/)
- [Documentation](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/quantum/data-plane/Microsoft.Quantum/preview/2026-01-15-preview)
- [OpenAPI](openapi/azure-quantum-data-plane-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-quantum-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-quantum-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-quantum-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-quantum-session-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-quantum-provider-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-quantum-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Azure Quantum Resource Manager API

Microsoft.Quantum Azure Resource Manager (ARM) control-plane API. Create, read, update, delete, and list Azure Quantum workspaces; list provider offerings per region; check workspace name availability; list and regenerate workspace keys; manage suite offers. Current preview version 2025-12-15-preview.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/templates/microsoft.quantum/workspaces](https://learn.microsoft.com/en-us/azure/templates/microsoft.quantum/workspaces)

#### Tags

- Quantum
- ARM
- Resource Manager
- Workspaces
- Provisioning

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/templates/microsoft.quantum/workspaces)
- [Documentation](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/quantum/resource-manager/Microsoft.Quantum/preview/2025-12-15-preview)
- [OpenAPI](openapi/azure-quantum-resource-manager-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-quantum-resource-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-quantum-resource-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Q# Quantum Programming Language

Q# is Microsoft's open-source, hardware-agnostic quantum programming language. The Modern QDK compiler is written in Rust, ships as a VS Code extension and Python package, and powers quantum.microsoft.com. Q# expresses programs as classical control-flow that operates on qubits without modeling the quantum state directly, and targets every Azure Quantum provider plus the Resource Estimator.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/quantum/qsharp-overview](https://learn.microsoft.com/en-us/azure/quantum/qsharp-overview)

#### Tags

- Quantum
- Programming Language
- Q#
- QDK
- Open Source

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/qsharp-overview)
- [Documentation](https://learn.microsoft.com/en-us/qsharp/api/)
- [GitHub Repository](https://github.com/microsoft/qdk)
- [GitHub Repository](https://github.com/microsoft/qsharp-language)
- [Postman Collection](collections/azure-quantum-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-quantum-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-quantum-resource-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-quantum-resource-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Quantum Resource Estimator

Open-source post-layout physical resource estimator for fault-tolerant quantum algorithms. Compute qubit counts, T-state counts, runtime, and code-distance requirements across configurable qubit physical parameters, QEC schemes, and error budgets. Ships inside the QDK and runs locally or as an Azure Quantum target.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/quantum/intro-to-resource-estimation](https://learn.microsoft.com/en-us/azure/quantum/intro-to-resource-estimation)

#### Tags

- Quantum
- Resource Estimation
- Fault Tolerance
- QEC

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/intro-to-resource-estimation)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/overview-resources-estimator)
- [GitHub Repository](https://github.com/microsoft/qdk)
- [Postman Collection](collections/azure-quantum-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-quantum-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-quantum-resource-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-quantum-resource-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Quantum Python SDK

Python SDK for submitting jobs to Azure Quantum. Supports Q#, Qiskit, Cirq, and pass-through provider input formats; manages workspaces, jobs, sessions, and target queries against the Workspace data-plane API.

- **Human URL:** [https://github.com/microsoft/azure-quantum-python](https://github.com/microsoft/azure-quantum-python)

#### Tags

- Quantum
- SDK
- Python
- Qiskit
- Cirq

#### Properties

- [GitHub Repository](https://github.com/microsoft/azure-quantum-python)
- [SDK](https://pypi.org/project/azure-quantum/)
- [Postman Collection](collections/azure-quantum-data-plane.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-quantum-data-plane.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-quantum-resource-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-quantum-resource-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://quantum.microsoft.com/)
- [Portal](https://azure.microsoft.com/en-us/products/quantum)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/quantum/overview-azure-quantum)
- [Getting Started](https://learn.microsoft.com/en-us/azure/quantum/install-overview-qdk)
- [Getting Started](https://learn.microsoft.com/en-us/azure/quantum/qsharp-quickstart)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/azurequantum/)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/qc-target-list)
- [Regions](https://learn.microsoft.com/en-us/azure/quantum/provider-global-availability)
- [Changelog](https://learn.microsoft.com/en-us/azure/quantum/release-notes)
- [Pricing](https://learn.microsoft.com/en-us/azure/quantum/pricing)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/azure-quantum-job-cost-billing)
- [Getting Started](https://learn.microsoft.com/en-us/azure/quantum/how-to-create-workspace)
- [Sign Up](https://ms.portal.azure.com/#create/Microsoft.AzureQuantum)
- [Sign Up](https://azure.microsoft.com/en-us/free/)
- [Sign Up](https://azure.microsoft.com/en-us/free/students/)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/credits)
- [Status Page](https://status.azure.com/)
- [Trust Center](https://www.microsoft.com/en-us/trust-center)
- [Terms of Service](https://learn.microsoft.com/en-us/legal/azure-quantum/)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Blog](https://cloudblogs.microsoft.com/quantum/)
- [Documentation](https://www.microsoft.com/research/research-area/quantum-computing/)
- [GitHub Organization](https://github.com/microsoft)
- [GitHub Organization](https://github.com/Azure)
- [Documentation](https://github.com/MicrosoftDocs/quantum-docs)
- [GitHub Repository](https://github.com/microsoft/qdk)
- [GitHub Repository](https://github.com/microsoft/qsharp-language)
- [GitHub Repository](https://github.com/microsoft/qsharp-compiler)
- [GitHub Repository](https://github.com/microsoft/qsharp-runtime)
- [GitHub Repository](https://github.com/microsoft/QuantumLibraries)
- [SDK](https://github.com/microsoft/azure-quantum-python)
- [SDK](https://pypi.org/project/azure-quantum/)
- [SDK](https://pypi.org/project/qsharp/)
- [Code Examples](https://github.com/microsoft/Quantum)
- [Courses](https://github.com/microsoft/QuantumKatas)
- [Courses](https://github.com/microsoft/quantum-curriculum-samples)
- [Tool](https://github.com/microsoft/iqsharp)
- [Tool](https://github.com/microsoft/quantum-viz.js)
- [Tool](https://github.com/microsoft/qdk-chemistry)
- [Tool](https://github.com/microsoft/Quantum-NC)
- [Tool](https://github.com/microsoft/qmt)
- [GitHub Repository](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/quantum)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/install-command-line-qdk)
- [Training](https://learn.microsoft.com/en-us/training/paths/quantum-computing-fundamentals/)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/hybrid-computing-overview)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/intro-to-resource-estimation)
- [Getting Started](https://learn.microsoft.com/en-us/azure/quantum/quickstart-microsoft-resources-estimator)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/qsharp-overview)
- [Documentation](https://learn.microsoft.com/en-us/qsharp/api/)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/provider-ionq)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/provider-quantinuum)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/provider-pasqal)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/provider-rigetti)
- [Documentation](https://learn.microsoft.com/en-us/azure/quantum/get-started-azure-quantum)
- [Forum](https://learn.microsoft.com/en-us/answers/tags/3/azure-quantum)
- [Plans](plans/microsoft-quantum-plans-pricing.yml)
- [Rate Limits](rate-limits/microsoft-quantum-rate-limits.yml)
- [Fin Ops](finops/microsoft-quantum-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com

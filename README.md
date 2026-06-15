# Microsoft Azure Quantum (microsoft-quantum)

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

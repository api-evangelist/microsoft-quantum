# Microsoft Azure Quantum (microsoft-quantum)

Microsoft Azure Quantum is Microsoft's cloud quantum computing service — an open, multi-vendor platform that provides access to quantum hardware from IonQ, Quantinuum, Pasqal, and Rigetti alongside Microsoft's own Q# programming language, Quantum Development Kit (QDK), and post-layout fault-tolerant Resource Estimator. The Azure Quantum Workspace REST API exposes jobs, sessions, providers, quotas, items, and storage surfaces; the Microsoft.Quantum ARM provider handles workspace provisioning. The QDK is free and open source, ships as a VS Code extension and Python package, and supports Q#, Qiskit, Cirq, and OpenQASM. Azure Quantum Elements layers in chemistry, materials, and HPC simulation for scientific discovery, with Copilot-assisted workflows on quantum.microsoft.com.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/microsoft-quantum/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Quantum, Quantum Computing, Azure, Microsoft, Q#, QDK, Resource Estimation, IonQ, Quantinuum, Pasqal, Rigetti, Hybrid Quantum, Fault Tolerance

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Hardware Providers

| Provider | Technology | Targets | Qubits |
|---|---|---|---|
| IonQ | Trapped ion | Aria 1, Forte 1, Forte Enterprise 1, simulator | 25 / 36 / 36 / 29 |
| Quantinuum | Trapped ion (QCCD) | H2-1, H2-2, H2 emulators, syntax checkers | 20 / 32 |
| Pasqal | Neutral atom | FRESNEL, FRESNEL_CAN1, EMU-MPS, EMU-SV, EMU_FREE | 100 / 100 / 80 / 25 / 12 |
| Rigetti | Superconducting | Cepheus-1-108Q, QVM simulator | 108 / 30 |
| Quantum Circuits (preview) | Superconducting + cQED | QCI (private preview) | TBA |

## APIs

### Azure Quantum Workspace Data-Plane API
Submit and manage quantum jobs, sessions, provider status, quotas, top-level items, and storage SAS URIs against an Azure Quantum workspace. Preview version `2026-01-15-preview`.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/azurequantum/](https://learn.microsoft.com/en-us/rest/api/azurequantum/)

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azurequantum/)
- [OpenAPI](openapi/azure-quantum-data-plane-openapi.json)
- [JSON Schema — Job](json-schema/azure-quantum-job-schema.json)
- [JSON Schema — Session](json-schema/azure-quantum-session-schema.json)
- [JSON Schema — Provider Status](json-schema/azure-quantum-provider-status-schema.json)
- [JSON-LD](json-ld/microsoft-quantum-context.jsonld)
- [Naftiko Capability — Jobs](capabilities/jobs-jobs.yaml)
- [Naftiko Capability — Sessions](capabilities/sessions-sessions.yaml)
- [Naftiko Capability — Providers](capabilities/providers-providers.yaml)
- [Naftiko Capability — Quotas](capabilities/quotas-quotas.yaml)
- [Naftiko Capability — Storage](capabilities/storage-storage.yaml)
- [Naftiko Capability — Items](capabilities/items-items.yaml)

### Azure Quantum Resource Manager API
Microsoft.Quantum ARM control-plane provider. Create, read, update, delete, list workspaces; list provider offerings per region; check name availability; manage workspace keys and suite offers. Preview version `2025-12-15-preview`.

**Human URL:** [https://learn.microsoft.com/en-us/azure/templates/microsoft.quantum/workspaces](https://learn.microsoft.com/en-us/azure/templates/microsoft.quantum/workspaces)

- [OpenAPI](openapi/azure-quantum-resource-manager-openapi.json)
- [Naftiko Capability — Workspaces](capabilities/workspaces-workspaces.yaml)
- [Naftiko Capability — Offerings](capabilities/offerings-offerings.yaml)

### Q# Quantum Programming Language
Microsoft's open-source, hardware-agnostic quantum programming language. Modern QDK compiler is written in Rust and ships as a VS Code extension and Python package.

**Human URL:** [https://learn.microsoft.com/en-us/azure/quantum/qsharp-overview](https://learn.microsoft.com/en-us/azure/quantum/qsharp-overview)

- [Q# Standard Library Reference](https://learn.microsoft.com/en-us/qsharp/api/)
- [Modern QDK Repository](https://github.com/microsoft/qdk)
- [Q# Language Design Repository](https://github.com/microsoft/qsharp-language)

### Microsoft Quantum Resource Estimator
Open-source post-layout physical resource estimator for fault-tolerant quantum algorithms. Compute qubit counts, T-state counts, runtime, and code-distance requirements across configurable qubit parameters and QEC schemes.

**Human URL:** [https://learn.microsoft.com/en-us/azure/quantum/intro-to-resource-estimation](https://learn.microsoft.com/en-us/azure/quantum/intro-to-resource-estimation)

### Azure Quantum Python SDK
Python SDK for submitting jobs to Azure Quantum. Supports Q#, Qiskit, Cirq, and pass-through provider formats.

**Human URL:** [https://github.com/microsoft/azure-quantum-python](https://github.com/microsoft/azure-quantum-python)

- `pip install azure-quantum`
- `pip install qsharp`

## Plans, Rate Limits, and FinOps

- [Plans and Pricing](plans/microsoft-quantum-plans-pricing.yml)
- [Rate Limits and Quotas](rate-limits/microsoft-quantum-rate-limits.yml)
- [FinOps / FOCUS Mapping](finops/microsoft-quantum-finops.yml)

## Key Resources

- [Microsoft Quantum site](https://quantum.microsoft.com/)
- [Azure Quantum docs](https://learn.microsoft.com/en-us/azure/quantum/)
- [Azure Quantum REST APIs](https://learn.microsoft.com/en-us/rest/api/azurequantum/)
- [Pricing](https://learn.microsoft.com/en-us/azure/quantum/pricing)
- [Provider Global Availability](https://learn.microsoft.com/en-us/azure/quantum/provider-global-availability)
- [QDK & Azure Quantum Release Notes](https://learn.microsoft.com/en-us/azure/quantum/release-notes)
- [Azure Quantum Blog](https://cloudblogs.microsoft.com/quantum/)
- [Microsoft Quantum Research](https://www.microsoft.com/research/research-area/quantum-computing/)
- [Azure REST API Specs — Quantum](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/quantum)

## Maintainers

- [Kin Lane](https://apievangelist.com) — info@apievangelist.com

<p align="center">
  <img src="https://raw.githubusercontent.com/open-omni-cloud/.github/main/assets/logo-open-omni-cloud.png" alt="Open Omni-Cloud Logo" width="150"/>
</p>

<h1 align="center">Open Omni-Cloud Initiative</h1>

<p align="center">
  <strong>Replacing marketing ambiguity with a verifiable, engineering-first standard for building truly cloud-agnostic systems.</strong>
</p>

<p align="center">
  <a href="https://github.com/open-omni-cloud/tck-py/actions/workflows/ci.yml"><img src="https://github.com/open-omni-cloud/tck-py/actions/workflows/ci.yml/badge.svg" alt="CI/CD Status"></a>
  <a href="https://raw.githubusercontent.com/open-omni-cloud/.github/LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="License: Apache 2.0"></a>
</p>

---

## The Mission: From Buzzwords to Blueprints

The multi-cloud paradigm promised flexibility but often delivered operational chaos and a new, insidious form of vendor lock-in. Most "multi-cloud" strategies fail to deliver true portability, resulting in higher operational complexity and a disguised form of vendor lock-in.

The **Open Omni-Cloud** initiative was created to fix this. Our mission is to build an ecosystem where cloud systems can be verified, tested, and trusted across providers. We believe in **Contracts Over Abstractions**: a verifiable, testable contract is what defines a standard, not lowest-common-denominator abstractions. We are building the open standard for the next generation of cloud architecture.

## What We Build: The Technology Compatibility Kit (TCK)

A contract is only as good as its enforcement. The core of our work is the **Technology Compatibility Kit (TCK)**, a `pytest`-based test suite that validates and certifies that a provider implementation adheres to the strict behavioral contracts of the Open Omni-Cloud standard.

A provider that successfully passes the TCK is guaranteed to be a **certified drop-in replacement**, enabling true portability and resilience by design.

## The Six Pillars of a Truly Omni-Cloud Architecture

Our standard is built upon six specific, verifiable criteria:

1.  **Agnostic Providers:** Interact with external dependencies through unified interfaces with consistent semantics.
2.  **A Technology Compatibility Kit (TCK):** A suite of automated tests that validates any provider implementation against the defined contract.
3.  **Swap by Configuration:** Switching between compliant providers must require only configuration changes, with zero refactoring of business code.
4.  **Cross-Cloud Failover Targets:** Demonstrated failover capabilities with pre-defined, aggressive, and tested recovery targets.
5.  **Standardized Observability:** First-class OpenTelemetry (traces, metrics, logs) and "Golden Signals" dashboards by default.
6.  **Portable Policies & Compliance:** Policies for data residency, encryption, and auditing must live inside the abstraction layer and travel with the workload.

## Our Projects

Our primary focus is the development and maintenance of the TCKs that enforce the standard.

-   **[tck-py](https://github.com/open-omni-cloud/tck-py)**: The official Technology Compatibility Kit (TCK) for Python implementations of the Open Omni-Cloud standard. It provides an executable contract for everything from primitives and messaging to resilience and observability patterns.

## 🤝 How to Get Involved

This is a community-driven initiative, and we invite engineers, providers, and organizations to join us in shaping a truly Omni-Cloud future.

| **Contribute Code** | **Sponsor the Initiative** | **Join the Discussion** |
| :--- | :--- | :--- |
| We are actively looking for contributors to help shape the future of cloud-agnostic computing. From fixing a typo to implementing a new contract, every contribution is valuable. See our **[Contribution Guide](hhttps://raw.githubusercontent.com/open-omni-cloud/.github/CONTRIBUTING.md)** to get started. | Our work is funded by the community. Your financial support helps us cover infrastructure costs and allows our core maintainers to dedicate more time to the project. Become a sponsor through our [TBD] | For questions, open ideas, or general discussions about the standard and its future, please join us on **[GitHub Discussions](https://github.com/open-omni-cloud/tck-py/discussions)**. |

## License

This project and all associated repositories are licensed under the **Apache 2.0 License**.
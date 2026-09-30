---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1357"
status: "Incomplete"
---
# CWE-1357: Reliance on Insufficiently Trustworthy Component

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Architecture-Specific, Not Technology-Specific, ICS/OT

## Description

The product is built from multiple separate components, but it uses a component that is not sufficiently trusted to meet expectations for security, reliability, updateability, and maintainability.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** For each component, ensure that its supply chain is well-controlled with sub-tier suppliers using best practices. For third-party software components such as libraries, ensure that they are developed and actively maintained by reputable vendors.
- **Architecture and Design:** Maintain a Bill of Materials for all components and sub-components of the product. For software, maintain a Software Bill of Materials (SBOM). According to [REF-1247], "An SBOM is a formal, machine-readable inventory of software components and dependencies, information about those components, and their hierarchical relationships."
- **Operation:** Continue to monitor changes in each of the product's components, especially when the changes indicate new vulnerabilities, end-of-life (EOL) plans, supplier practices that affect trustworthiness, etc.

## Related weaknesses

- CWE-710 (ChildOf)

## Source

- [CWE-1357 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1357.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

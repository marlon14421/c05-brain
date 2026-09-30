---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1395"
status: "Incomplete"
---
# CWE-1395: Dependency on Vulnerable Third-Party Component

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product has a dependency on a third-party component that contains one or more known vulnerabilities.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** In some industries such as healthcare [REF-1320] [REF-1322] or technologies such as the cloud [REF-1321], it might be unclear about who is responsible for applying patches for third-party vulnerabilities: the vendor, the operator/customer, or a separate service. Clarifying roles and responsibilities can be important to minimize confusion or unnecessary delay when third-party vulnerabilities are disclosed.
- **Requirements:** Require a Bill of Materials for all components and sub-components of the product. For software, require a Software Bill of Materials (SBOM) [REF-1247] [REF-1311].
- **Architecture and Design:** Maintain a Bill of Materials for all components and sub-components of the product. For software, maintain a Software Bill of Materials (SBOM). According to [REF-1247], "An SBOM is a formal, machine-readable inventory of software components and dependencies, information about those components, and their hierarchical relationships."
- **Operation:** Actively monitor when a third-party component vendor announces vulnerability patches; fix the third-party component as soon as possible; and make it easy for operators/customers to obtain and apply the patch.
- **Operation:** Continuously monitor changes in each of the product's components, especially when the changes indicate new vulnerabilities, end-of-life (EOL) plans, etc.

## Related weaknesses

- CWE-1357 (ChildOf)
- CWE-657 (ChildOf)

## Source

- [CWE-1395 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1395.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

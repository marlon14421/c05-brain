---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-520"
status: "Incomplete"
---
# CWE-520: .NET Misconfiguration: Use of Impersonation

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, ASP.NET, VB.NET, Not Technology-Specific, Web Based

## Description

Allowing a .NET application to run at potentially escalated levels of access to the underlying operating and file systems can be dangerous and result in various forms of attacks.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Operation:** Run the application with limited privilege to the underlying operating and file system.

## Related weaknesses

- CWE-266 (ChildOf)

## Source

- [CWE-520 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/520.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

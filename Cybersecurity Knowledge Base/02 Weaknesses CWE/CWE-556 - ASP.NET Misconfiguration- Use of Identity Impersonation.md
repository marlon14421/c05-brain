---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-556"
status: "Incomplete"
---
# CWE-556: ASP.NET Misconfiguration: Use of Identity Impersonation

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** ASP.NET

## Description

Configuring an ASP.NET application to run with impersonated credentials may give the application unnecessary privileges.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use the least privilege principle.

## Related weaknesses

- CWE-266 (ChildOf)

## Source

- [CWE-556 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/556.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

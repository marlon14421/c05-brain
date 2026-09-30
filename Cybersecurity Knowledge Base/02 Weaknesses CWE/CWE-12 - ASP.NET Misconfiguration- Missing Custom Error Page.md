---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-12"
status: "Draft"
---
# CWE-12: ASP.NET Misconfiguration: Missing Custom Error Page

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** ASP.NET

## Description

An ASP .NET application must enable custom error pages in order to prevent attackers from mining information from the framework's built-in responses.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **System Configuration:** Handle exceptions appropriately in source code. ASP .NET applications should be configured to use custom error pages instead of the framework default page.
- **Architecture and Design:** Do not attempt to process an error or attempt to mask it.
- **Implementation:** Verify return values are correct and do not supply sensitive information about the system.

## Related weaknesses

- CWE-756 (ChildOf)

## Source

- [CWE-12 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/12.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

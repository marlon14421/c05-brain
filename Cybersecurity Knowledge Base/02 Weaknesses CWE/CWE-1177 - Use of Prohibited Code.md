---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1177"
status: "Incomplete"
---
# CWE-1177: Use of Prohibited Code

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product uses a function, library, or third party component that has been explicitly prohibited, whether by the developer or the customer.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Build and Compilation:** Identify a list of prohibited API functions and prohibit developers from using these functions, providing safer alternatives. In some cases, automatic code analysis tools or the compiler can be instructed to spot use of prohibited functions, such as the "banned.h" include file from Microsoft's SDL. [REF-554] [REF-1009] [REF-7]

## Related weaknesses

- CWE-710 (ChildOf)

## Source

- [CWE-1177 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1177.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

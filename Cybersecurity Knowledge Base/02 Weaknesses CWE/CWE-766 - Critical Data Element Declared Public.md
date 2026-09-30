---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-766"
status: "Incomplete"
---
# CWE-766: Critical Data Element Declared Public

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C++, C#, Java

## Description

The product declares a critical variable, field, or member to be public when intended security policy requires it to be private.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Data should be private, static, and final whenever possible. This will assure that your code is protected by instantiating early, preventing access, and preventing tampering.

## Related weaknesses

- CWE-732 (ChildOf)
- CWE-1061 (ChildOf)

## Source

- [CWE-766 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/766.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

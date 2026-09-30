---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-506"
status: "Incomplete"
---
# CWE-506: Embedded Malicious Code

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product contains code that appears to be malicious in nature.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Remove the malicious code and start an effort to ensure that no more malicious code exists. This may require a detailed review of all code, as it is possible to hide a serious attack in only one or two lines of code. These lines may be located almost anywhere in an application and may have been intentionally obfuscated by the attacker.

## Related weaknesses

- CWE-912 (ChildOf)

## Source

- [CWE-506 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/506.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

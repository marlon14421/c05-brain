---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-655"
status: "Draft"
---
# CWE-655: Insufficient Psychological Acceptability

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product has a protection mechanism that is too difficult or inconvenient to use, encouraging non-malicious users to disable or bypass the mechanism, whether by accident or on purpose.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Testing:** Where possible, perform human factors and usability studies to identify where your product's security mechanisms are difficult to use, and why.
- **Architecture and Design:** Make the security mechanism as seamless as possible, while also providing the user with sufficient details when a security decision produces unexpected results.

## Related weaknesses

- CWE-657 (ChildOf)
- CWE-693 (ChildOf)

## Source

- [CWE-655 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/655.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

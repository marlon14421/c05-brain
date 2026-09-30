---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-550"
status: "Incomplete"
---
# CWE-550: Server-generated Error Message Containing Sensitive Information

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

Certain conditions, such as network failure, will cause a server error message to be displayed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Recommendations include designing and adding consistent error handling mechanisms which are capable of handling any user input to your web application, providing meaningful detail to end-users, and preventing error messages that might provide information useful to an attacker from being displayed.

## Related weaknesses

- CWE-209 (ChildOf)

## Source

- [CWE-550 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/550.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

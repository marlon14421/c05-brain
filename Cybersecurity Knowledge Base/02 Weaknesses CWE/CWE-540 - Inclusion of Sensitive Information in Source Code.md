---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-540"
status: "Incomplete"
---
# CWE-540: Inclusion of Sensitive Information in Source Code

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based

## Description

Source code on a web server or repository often contains sensitive information and should generally not be accessible to users.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Recommendations include removing this script from the web server and moving it to a location not accessible from the Internet.

## Related weaknesses

- CWE-538 (ChildOf)

## Source

- [CWE-540 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/540.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-615"
status: "Incomplete"
---
# CWE-615: Inclusion of Sensitive Information in Source Code Comments

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

While adding general comments is very useful, some programmers tend to leave important data, such as: filenames related to the web application, old links or links which were not meant to be browsed by users, old code fragments, etc.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Distribution:** Remove comments which have sensitive information about the design/implementation of the application. Some of the comments may be exposed to the user and affect the security posture of the application.

## Related weaknesses

- CWE-540 (ChildOf)
- CWE-546 (PeerOf)

## Source

- [CWE-615 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/615.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-262"
status: "Draft"
---
# CWE-262: Not Using Password Aging

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not have a mechanism in place for managing password aging.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** As part of a product's design, require users to change their passwords regularly and avoid reusing previous passwords.
- **Implementation:** Developers might disable clipboard paste operations into password fields as a way to discourage users from pasting a password into a clipboard. However, this might encourage users to choose less-secure passwords that are easier to type, and it can reduce the usability of password managers [REF-1294].

## Related weaknesses

- CWE-1390 (ChildOf)
- CWE-309 (PeerOf)
- CWE-324 (PeerOf)

## Source

- [CWE-262 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/262.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

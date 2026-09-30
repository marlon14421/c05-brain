---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-243"
status: "Draft"
---
# CWE-243: Creation of chroot Jail Without Changing Working Directory

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Unix

## Description

The product uses the chroot() system call to create a jail, but does not change the working directory afterward. This does not prevent access to files outside of the jail.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-573 (ChildOf)
- CWE-669 (ChildOf)

## Source

- [CWE-243 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/243.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

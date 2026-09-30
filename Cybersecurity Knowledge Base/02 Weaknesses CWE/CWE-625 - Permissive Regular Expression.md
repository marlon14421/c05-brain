---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-625"
status: "Draft"
---
# CWE-625: Permissive Regular Expression

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Perl, PHP

## Description

The product uses a regular expression that does not sufficiently restrict the set of allowed values.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When applicable, ensure that the regular expression marks beginning and ending string patterns, such as "/^string$/" for Perl.

## Related weaknesses

- CWE-185 (ChildOf)
- CWE-187 (PeerOf)
- CWE-184 (PeerOf)
- CWE-183 (PeerOf)

## Source

- [CWE-625 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/625.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

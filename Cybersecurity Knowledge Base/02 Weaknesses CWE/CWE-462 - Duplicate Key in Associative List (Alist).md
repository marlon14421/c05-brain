---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-462"
status: "Incomplete"
---
# CWE-462: Duplicate Key in Associative List (Alist)

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++, Java, C#

## Description

Duplicate keys in associative lists can lead to non-unique keys being mistaken for an error.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use a hash table instead of an alist.
- **Architecture and Design:** Use an alist which checks the uniqueness of hash keys with each entry before inserting the entry.

## Related weaknesses

- CWE-694 (ChildOf)

## Source

- [CWE-462 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/462.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

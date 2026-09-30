---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-594"
status: "Incomplete"
---
# CWE-594: J2EE Framework: Saving Unserializable Objects to Disk

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java, Web Based, Web Server

## Description

When the J2EE container attempts to write unserializable objects to disk there is no guarantee that the process will complete successfully.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** All objects that become part of session and application scope must implement the java.io.Serializable interface to ensure serializability of containing objects.

## Related weaknesses

- CWE-1076 (ChildOf)

## Source

- [CWE-594 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/594.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

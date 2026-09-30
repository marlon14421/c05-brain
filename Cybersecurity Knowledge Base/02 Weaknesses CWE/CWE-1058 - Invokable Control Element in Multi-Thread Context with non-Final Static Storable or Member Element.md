---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1058"
status: "Incomplete"
---
# CWE-1058: Invokable Control Element in Multi-Thread Context with non-Final Static Storable or Member Element

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The code contains a function or method that operates in a multi-threaded environment but owns an unsafe non-final static storable or member data element.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-662 (ChildOf)
- CWE-662 (ChildOf)
- CWE-662 (ChildOf)

## Source

- [CWE-1058 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1058.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

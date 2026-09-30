---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-939"
status: "Incomplete"
---
# CWE-939: Improper Authorization in Handler for Custom URL Scheme

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Mobile

## Description

The product uses a handler for a custom URL scheme, but it does not properly restrict which actors can invoke the handler using the scheme.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-862 (ChildOf)
- CWE-940 (ChildOf)

## Source

- [CWE-939 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/939.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

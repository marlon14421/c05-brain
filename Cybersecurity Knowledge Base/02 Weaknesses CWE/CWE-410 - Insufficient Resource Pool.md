---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-410"
status: "Incomplete"
---
# CWE-410: Insufficient Resource Pool

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product's resource pool is not large enough to handle peak demand, which allows an attacker to prevent others from accessing the resource by using a (relatively) large number of requests for resources.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not perform resource-intensive transactions for unauthenticated users and/or invalid requests.
- **Architecture and Design:** Consider implementing a velocity check mechanism which would detect abusive behavior.
- **Operation:** Consider load balancing as an option to handle heavy loads.
- **Implementation:** Make sure that resource handles are properly closed when no longer needed.
- **Architecture and Design:** Identify the system's resource intensive operations and consider protecting them from abuse (e.g. malicious automated script which runs the resources out).

## Related weaknesses

- CWE-664 (ChildOf)
- CWE-400 (CanPrecede)

## Source

- [CWE-410 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/410.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-350"
status: "Draft"
---
# CWE-350: Reliance on Reverse DNS Resolution for a Security-Critical Action

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product performs reverse DNS resolution on an IP address to obtain the hostname and make a security decision, but it does not properly ensure that the IP address is truly associated with the hostname.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use other means of identity verification that cannot be simply spoofed. Possibilities include a username/password or certificate.
- **Implementation:** Perform proper forward and reverse DNS lookups to detect DNS spoofing.

## Related weaknesses

- CWE-290 (ChildOf)
- CWE-807 (ChildOf)
- CWE-923 (CanPrecede)

## Source

- [CWE-350 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/350.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

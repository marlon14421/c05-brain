---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1327"
status: "Incomplete"
---
# CWE-1327: Binding to an Unrestricted IP Address

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Other, Not OS-Specific, Not Architecture-Specific, Web Server, Client Server, Cloud Computing

## Description

The product assigns the address 0.0.0.0 for a database server, a cloud service/instance, or any computing resource that communicates remotely.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **System Configuration:** Assign IP addresses that are not 0.0.0.0.
- **System Configuration:** Unwanted connections to the configured server may be denied through a firewall or other packet filtering measures.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-1327 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1327.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

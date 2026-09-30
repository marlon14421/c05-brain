---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-405"
status: "Incomplete"
---
# CWE-405: Asymmetric Resource Consumption (Amplification)

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific, Client Server

## Description

The product does not properly control situations in which an adversary can cause the product to consume or produce excessive resources without requiring the adversary to invest equivalent work or otherwise prove authorization, i.e., the adversary's influence is "asymmetric."

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** An application must make resources available to a client commensurate with the client's access level.
- **Architecture and Design:** An application must, at all times, keep track of allocated resources and meter their usage appropriately.
- **System Configuration:** Consider disabling resource-intensive algorithms on the server side, such as Diffie-Hellman key exchange.

## Related weaknesses

- CWE-400 (ChildOf)

## Source

- [CWE-405 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/405.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

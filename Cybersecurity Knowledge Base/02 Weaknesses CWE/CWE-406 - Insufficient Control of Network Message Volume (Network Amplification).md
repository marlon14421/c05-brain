---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-406"
status: "Incomplete"
---
# CWE-406: Insufficient Control of Network Message Volume (Network Amplification)

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product does not sufficiently monitor or control transmitted network traffic volume, so that an actor can cause the product to transmit more traffic than should be allowed for that actor.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** An application must make network resources available to a client commensurate with the client's access level.
- **Policy:** Define a clear policy for network resource allocation and consumption.
- **Implementation:** An application must, at all times, keep track of network resources and meter their usage appropriately.

## Related weaknesses

- CWE-405 (ChildOf)

## Source

- [CWE-406 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/406.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

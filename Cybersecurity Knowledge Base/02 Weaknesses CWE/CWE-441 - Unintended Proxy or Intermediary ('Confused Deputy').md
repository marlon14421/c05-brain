---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-441"
status: "Draft"
---
# CWE-441: Unintended Proxy or Intermediary ('Confused Deputy')

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product receives a request, message, or directive from an upstream component, but the product does not sufficiently preserve the original source of the request before forwarding the request to an external actor that is outside of the product's control sphere. This causes the product to appear to be the source of the request, leading it to act as a proxy or other intermediary between the upstream component and the external actor.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Enforce the use of strong mutual authentication mechanism between the two parties.
- **Architecture and Design:** Whenever a product is an intermediary or proxy for transactions between two other components, the proxy core should not drop the identity of the initiator of the transaction. The immutability of the identity of the initiator must be maintained and should be forwarded all the way to the target.

## Related weaknesses

- CWE-610 (ChildOf)
- CWE-668 (CanPrecede)

## Source

- [CWE-441 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/441.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

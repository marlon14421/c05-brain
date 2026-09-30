---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-827"
status: "Incomplete"
---
# CWE-827: Improper Control of Document Type Definition

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** XML

## Description

The product does not restrict a reference to a Document Type Definition (DTD) to the intended control sphere. This might allow attackers to reference arbitrary DTDs, possibly causing the product to expose files, consume excessive system resources, or execute arbitrary http requests on behalf of the attacker.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-706 (ChildOf)
- CWE-829 (ChildOf)
- CWE-776 (CanPrecede)

## Source

- [CWE-827 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/827.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

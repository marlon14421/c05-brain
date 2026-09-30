---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-509"
status: "Incomplete"
---
# CWE-509: Replicating Malicious Code (Virus or Worm)

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

Replicating malicious code, including viruses and worms, will attempt to attack other systems once it has successfully compromised the target system or the product.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Operation:** Antivirus software scans for viruses or worms.
- **Installation:** Always verify the integrity of the software that is being installed.

## Related weaknesses

- CWE-507 (ChildOf)

## Source

- [CWE-509 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/509.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

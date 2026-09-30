---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-508"
status: "Incomplete"
---
# CWE-508: Non-Replicating Malicious Code

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

Non-replicating malicious code only resides on the target system or product that is attacked; it does not attempt to spread to other systems.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Operation:** Antivirus software can help mitigate known malicious code.
- **Installation:** Verify the integrity of the software that is being installed.

## Related weaknesses

- CWE-507 (ChildOf)

## Source

- [CWE-508 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/508.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

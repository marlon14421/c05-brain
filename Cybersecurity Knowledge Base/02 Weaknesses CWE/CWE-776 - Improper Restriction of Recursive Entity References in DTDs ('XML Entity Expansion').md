---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-776"
status: "Draft"
---
# CWE-776: Improper Restriction of Recursive Entity References in DTDs ('XML Entity Expansion')

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, XML, Not Technology-Specific

## Description

The product uses XML documents and allows their structure to be defined with a Document Type Definition (DTD), but it does not properly control the number of recursive definitions of entities.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Operation:** If possible, prohibit the use of DTDs or use an XML parser that limits the expansion of recursive DTD entities.
- **Implementation:** Before parsing XML files with associated DTDs, scan for recursive entity declarations and do not continue parsing potentially explosive content.

## Related weaknesses

- CWE-674 (ChildOf)
- CWE-674 (ChildOf)
- CWE-405 (ChildOf)

## Source

- [CWE-776 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/776.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

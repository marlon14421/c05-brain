---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-643"
status: "Incomplete"
---
# CWE-643: Improper Neutralization of Data within XPath Expressions ('XPath Injection')

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product uses external input to dynamically construct an XPath expression used to retrieve data from an XML database, but it does not neutralize or incorrectly neutralizes that input. This allows an attacker to control the structure of the query.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use parameterized XPath queries (e.g. using XQuery). This will help ensure separation between data plane and control plane.
- **Implementation:** Properly validate user input. Reject data where appropriate, filter where appropriate and escape where appropriate. Make sure input that will be used in XPath queries is safe in that context.

## Related weaknesses

- CWE-943 (ChildOf)
- CWE-91 (ChildOf)

## Source

- [CWE-643 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/643.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

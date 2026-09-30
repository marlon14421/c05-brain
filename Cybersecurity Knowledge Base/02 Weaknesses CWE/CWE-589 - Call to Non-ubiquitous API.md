---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-589"
status: "Incomplete"
---
# CWE-589: Call to Non-ubiquitous API

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product uses an API function that does not exist on all versions of the target platform. This could cause portability problems or inconsistencies that allow denial of service or other consequences.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Always test your code on any platform on which it is targeted to run on.
- **Testing:** Test your code on the newest and oldest platform on which it is targeted to run on.
- **Testing:** Develop a system to test for API functions that are not portable.

## Related weaknesses

- CWE-474 (ChildOf)

## Source

- [CWE-589 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/589.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

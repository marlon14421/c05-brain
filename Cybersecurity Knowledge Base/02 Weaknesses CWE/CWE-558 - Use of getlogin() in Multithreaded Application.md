---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-558"
status: "Draft"
---
# CWE-558: Use of getlogin() in Multithreaded Application

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

The product uses the getlogin() function in a multithreaded context, potentially causing it to return incorrect values.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Using names for security purposes is not advised. Names are easy to forge and can have overlapping user IDs, potentially causing confusion or impersonation.
- **Implementation:** Use getlogin_r() instead, which is reentrant, meaning that other processes are locked out from changing the username.

## Related weaknesses

- CWE-663 (ChildOf)

## Source

- [CWE-558 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/558.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

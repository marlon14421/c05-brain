---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-566"
status: "Incomplete"
---
# CWE-566: Authorization Bypass Through User-Controlled SQL Primary Key

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** SQL, Database Server

## Description

The product uses a database table that includes records that should not be accessible to an actor, but it executes a SQL statement with a primary key that can be controlled by that actor.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Assume all input is malicious. Use a standard input validation mechanism to validate all input for length, type, syntax, and business rules before accepting the data. Use an "accept known good" validation strategy.
- **Implementation:** Use a parameterized query AND make sure that the accepted values conform to the business rules. Construct your SQL statement accordingly.

## Related weaknesses

- CWE-639 (ChildOf)

## Source

- [CWE-566 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/566.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

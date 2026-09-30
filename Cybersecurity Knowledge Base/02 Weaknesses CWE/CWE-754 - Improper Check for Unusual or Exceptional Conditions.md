---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-754"
status: "Incomplete"
---
# CWE-754: Improper Check for Unusual or Exceptional Conditions

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product does not check or incorrectly checks for unusual or exceptional conditions that are not expected to occur frequently during day to day operation of the product.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Check the results of all functions that return a value and verify that the value is expected.
- **Implementation:** If using exception handling, catch and throw specific exceptions instead of overly-general exceptions (CWE-396, CWE-397). Catch and handle exceptions as locally as possible so that exceptions do not propagate too far up the call stack (CWE-705). Avoid unchecked or uncaught exceptions where feasible (CWE-248).
- **Architecture and Design:** If the program must fail, ensure that it fails gracefully (fails closed). There may be a temptation to simply let the program fail poorly in cases such as low memory conditions, but an attacker may be able to assert control before the software has fully exited. Alternately, an uncontrolled failure could cause cascading problems with other downstream components; for example, the program could send a signal to a downstream process so the process immediately knows that a problem has occurred and has a better chance of recovery.
- **Architecture and Design:** Use system limits, which should help to prevent resource exhaustion. However, the product should still handle low resource conditions since they may still occur.

## Related weaknesses

- CWE-703 (ChildOf)
- CWE-416 (CanPrecede)

## Source

- [CWE-754 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/754.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

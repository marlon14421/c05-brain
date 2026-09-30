---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-805"
status: "Incomplete"
---
# CWE-805: Buffer Access with Incorrect Length Value

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Memory-Unsafe, C, C++, Assembly

## Description

The product uses a sequential operation to read or write a buffer, but it uses an incorrect length value that causes it to access memory that is outside of the bounds of the buffer.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** For any security checks that are performed on the client side, ensure that these checks are duplicated on the server side, in order to avoid CWE-602. Attackers can bypass the client-side checks by modifying values after the checks have been performed, or by changing the client to remove the client-side checks entirely. Then, these modified values would be submitted to the server.
- **Architecture and Design:** Run your code using the lowest privileges that are required to accomplish the necessary tasks [REF-76]. If possible, create isolated accounts with limited privileges that are only used for a single task. That way, a successful attack will not immediately give the attacker access to the rest of the product or its environment. For example, database applications rarely need to run as the database administrator, especially in day-to-day operations.

## Related weaknesses

- CWE-119 (ChildOf)
- CWE-119 (ChildOf)
- CWE-119 (ChildOf)

## Source

- [CWE-805 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/805.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

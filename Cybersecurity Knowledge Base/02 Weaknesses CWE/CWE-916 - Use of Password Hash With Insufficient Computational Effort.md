---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-916"
status: "Incomplete"
---
# CWE-916: Use of Password Hash With Insufficient Computational Effort

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product generates a hash for a password, but it uses a scheme that does not provide a sufficient level of computational effort that would make password cracking attacks infeasible or expensive.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When using industry-approved techniques, use them correctly. Don't cut corners by skipping resource-intensive steps (CWE-325). These steps are often essential for preventing common attacks.

## Related weaknesses

- CWE-328 (ChildOf)
- CWE-327 (ChildOf)

## Source

- [CWE-916 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/916.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

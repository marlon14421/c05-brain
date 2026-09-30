---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1269"
status: "Incomplete"
---
# CWE-1269: Product Released in Non-Release Configuration

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** VHDL, Verilog, Compiled, Not OS-Specific, Not Architecture-Specific, Other, Not Technology-Specific

## Description

The product released to market is released in pre-production or manufacturing configuration.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that there exists a marker for denoting the Manufacturing Complete stage and that the Manufacturing Complete marker gets updated at the Manufacturing Complete stage (i.e., the Manufacturing Complete fuse gets blown).
- **Integration:** Ensure that there exists a marker for denoting the Manufacturing Complete stage and that the Manufacturing Complete marker gets updated at the Manufacturing Complete stage (i.e., the Manufacturing Complete fuse gets blown).
- **Manufacturing:** Ensure that there exists a marker for denoting the Manufacturing Complete stage and that the Manufacturing Complete marker gets updated at the Manufacturing Complete stage (i.e., the Manufacturing Complete fuse gets blown).

## Related weaknesses

- CWE-693 (ChildOf)

## Source

- [CWE-1269 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1269.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

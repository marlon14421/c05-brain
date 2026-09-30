---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-473"
status: "Draft"
---
# CWE-473: PHP External Variable Modification

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** PHP

## Description

A PHP application does not properly protect against the modification of variables from external sources, such as query parameters or cookies. This can expose the application to numerous weaknesses that would not exist otherwise.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Carefully identify which variables can be controlled or influenced by an external user, and consider adopting a naming convention to emphasize when externally modifiable variables are being used. An application should be reluctant to trust variables that have been initialized outside of its trust boundary. Ensure adequate checking is performed when relying on input from outside a trust boundary. Do not allow your application to run with register_globals enabled. If you implement a register_globals emulator, be extremely careful of variable extraction, dynamic evaluation, and similar issues, since weaknesses in your emulation could allow external variable modification to take place even without register_globals.

## Related weaknesses

- CWE-471 (ChildOf)
- CWE-98 (CanPrecede)

## Source

- [CWE-473 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/473.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-382"
status: "Draft"
---
# CWE-382: J2EE Bad Practices: Use of System.exit()

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java, Web Based, Web Server

## Description

A J2EE application uses System.exit(), which also shuts down its container.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** The shutdown function should be a privileged function available only to a properly authorized administrative user
- **Implementation:** Web applications should not call methods that cause the virtual machine to exit, such as System.exit()
- **Implementation:** Web applications should also not throw any Throwables to the application server as this may adversely affect the container.
- **Implementation:** Non-web applications may have a main() method that contains a System.exit(), but generally should not call System.exit() from other locations in the code

## Related weaknesses

- CWE-705 (ChildOf)

## Source

- [CWE-382 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/382.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

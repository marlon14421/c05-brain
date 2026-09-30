---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-209"
status: "Draft"
---
# CWE-209: Generation of Error Message Containing Sensitive Information

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** PHP, Java, Not Language-Specific, Not Technology-Specific

## Description

The product generates an error message that includes sensitive information about its environment, users, or associated data.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Handle exceptions internally and do not display errors containing potentially sensitive information to a user.
- **Implementation:** Use naming conventions and strong types to make it easier to spot when sensitive data is being used. When creating structures, objects, or other complex entities, separate the sensitive and non-sensitive data as much as possible.
- **Implementation:** Debugging information should not make its way into a production release.
- **Implementation:** Debugging information should not make its way into a production release.
- **System Configuration:** Where available, configure the environment to use less verbose error messages. For example, in PHP, disable the display_errors setting during configuration, or at runtime using the error_reporting() function.
- **System Configuration:** Create default error pages or messages that do not leak any information.

## Related weaknesses

- CWE-200 (ChildOf)
- CWE-200 (ChildOf)
- CWE-755 (ChildOf)

## Source

- [CWE-209 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/209.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-641"
status: "Incomplete"
---
# CWE-641: Improper Restriction of Names for Files and Other Resources

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product constructs the name of a file or other resource using input from an upstream component, but it does not restrict or incorrectly restricts the resulting name.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not allow users to control names of resources used on the server side.
- **Architecture and Design:** Perform allowlist input validation at entry points and also before consuming the resources. Reject bad file names rather than trying to cleanse them.
- **Architecture and Design:** Make sure that technologies consuming the resources are not vulnerable (e.g. buffer overflow, format string, etc.) in a way that would allow code execution if the name of the resource is malformed.

## Related weaknesses

- CWE-99 (ChildOf)

## Source

- [CWE-641 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/641.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

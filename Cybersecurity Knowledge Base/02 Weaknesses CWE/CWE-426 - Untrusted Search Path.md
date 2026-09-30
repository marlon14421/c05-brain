---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-426"
status: "Stable"
---
# CWE-426: Untrusted Search Path

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not OS-Specific

## Description

The product searches for critical resources using an externally-supplied search path that can point to resources that are not under the product's direct control.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Hard-code the search path to a set of known-safe values (such as system directories), or only allow them to be specified by the administrator in a configuration file. Do not allow these settings to be modified by an external party. Be careful to avoid related weaknesses such as CWE-426 and CWE-428.
- **Implementation:** When invoking other programs, specify those programs using fully-qualified pathnames. While this is an effective approach, code that uses fully-qualified pathnames might not be portable to other systems that do not use the same pathnames. The portability can be improved by locating the full-qualified paths in a centralized, easily-modifiable location within the source code, and having the code refer to these paths.
- **Implementation:** Remove or restrict all environment settings before invoking other programs. This includes the PATH environment variable, LD_LIBRARY_PATH, and other settings that identify the location of code libraries, and any application-specific search paths.
- **Implementation:** Check your search path before use and remove any elements that are likely to be unsafe, such as the current working directory or a temporary files directory.
- **Implementation:** Use other functions that require explicit paths. Making use of any of the other readily available functions that require explicit paths is a safe way to avoid this problem. For example, system() in C does not require a full path since the shell can take care of it, while execl() and execv() require a full path.

## Related weaknesses

- CWE-642 (ChildOf)
- CWE-668 (ChildOf)
- CWE-673 (ChildOf)
- CWE-427 (PeerOf)
- CWE-428 (PeerOf)

## Source

- [CWE-426 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/426.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

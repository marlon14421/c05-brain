---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1299"
status: "Draft"
---
# CWE-1299: Missing Protection Mechanism for Alternate Hardware Interface

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Microcontroller Hardware, Processor Hardware, Bus/Interface Hardware, Not Technology-Specific

## Description

The lack of protections on alternate paths to access control-protected assets (such as unprotected shadow registers and other external facing unguarded interfaces) allows an attacker to bypass existing protections to the asset that are only performed against the primary path.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Protect assets from accesses against all potential interfaces and alternate paths.
- **Architecture and Design:** Protect assets from accesses against all potential interfaces and alternate paths.
- **Implementation:** Protect assets from accesses against all potential interfaces and alternate paths.

## Related weaknesses

- CWE-1191 (PeerOf)
- CWE-420 (ChildOf)
- CWE-288 (ChildOf)

## Source

- [CWE-1299 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1299.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).

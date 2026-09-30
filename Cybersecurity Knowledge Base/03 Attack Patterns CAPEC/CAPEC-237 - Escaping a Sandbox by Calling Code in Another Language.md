---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-237"
status: "Draft"
---
# CAPEC-237: Escaping a Sandbox by Calling Code in Another Language

**Abstraction:** Detailed  
**Catalog severity:** Very High  
**Catalog likelihood:** Low

## Description

The attacker may submit malicious code of another language to obtain access to privileges that were not intentionally exposed by the sandbox, thus escaping the sandbox. For instance, Java code cannot perform unsafe operations, such as modifying arbitrary memory locations, due to restrictions placed on it by the Byte code Verifier and the JVM. If allowed, Java code can call directly into native C code, which may perform unsafe operations, such as call system calls and modify arbitrary memory locations on their behalf. To provide isolation, Java does not grant untrusted code with unmediated access to native C code. Instead, the sandboxed code is typically allowed to call some subset of the pre-existing native code that is part of standard libraries.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-237 on capec.mitre.org](https://capec.mitre.org/data/definitions/237.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).

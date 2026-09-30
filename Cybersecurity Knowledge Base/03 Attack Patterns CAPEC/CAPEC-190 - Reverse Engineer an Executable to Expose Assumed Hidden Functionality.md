---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-190"
status: "Draft"
---
# CAPEC-190: Reverse Engineer an Executable to Expose Assumed Hidden Functionality

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Not stated

## Description

An attacker analyzes a binary file or executable for the purpose of discovering the structure, function, and possibly source-code of the file by using a variety of analysis techniques to effectively determine how the software functions and operates. This type of analysis is also referred to as Reverse Code Engineering, as techniques exist for extracting source code from an executable. Several techniques are often employed for this purpose, both black box and white box. The use of computer bus analyzers and packet sniffers allows the binary to be studied at a level of interactions with its computing environment, such as a host OS, inter-process communication, and/or network communication. This type of analysis falls into the 'black box' category because it involves behavioral analysis of the software without reference to source code, object code, or protocol specifications.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-190 on capec.mitre.org](https://capec.mitre.org/data/definitions/190.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).

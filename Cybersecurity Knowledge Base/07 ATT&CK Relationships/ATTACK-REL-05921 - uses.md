---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0219"
target_object: "T1059"
stix_relationship_id: "relationship--819a5c4e-2bd6-4d9b-844c-21dc31e85a67"
---
# Relationship 5921: S0219 — uses → T1059

**Source object:** [[01 ATT&CK/S0219 - WINERACK|S0219: WINERACK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059 - Command and Scripting Interpreter|T1059: Command and Scripting Interpreter]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WINERACK](https://attack.mitre.org/software/S0219) can create a reverse shell that utilizes statically-linked Wine cmd.exe code to emulate Windows command prompt commands.(Citation: FireEye APT37 Feb 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--819a5c4e-2bd6-4d9b-844c-21dc31e85a67`.

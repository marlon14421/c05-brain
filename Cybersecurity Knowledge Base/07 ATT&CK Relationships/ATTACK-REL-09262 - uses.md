---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1030"
target_object: "T1059.003"
stix_relationship_id: "relationship--e3f48900-e929-4040-8e7b-13d06933ce1d"
---
# Relationship 9262: S1030 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1030 - Squirrelwaffle|S1030: Squirrelwaffle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Squirrelwaffle](https://attack.mitre.org/software/S1030) has used `cmd.exe` for execution.(Citation: Netskope Squirrelwaffle Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3f48900-e929-4040-8e7b-13d06933ce1d`.

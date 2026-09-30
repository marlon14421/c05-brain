---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0258"
target_object: "T1059.003"
stix_relationship_id: "relationship--2d467445-9cce-4e84-968e-7a7ecc0a81fa"
---
# Relationship 7082: S0258 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0258 - RGDoor|S0258: RGDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RGDoor](https://attack.mitre.org/software/S0258) uses cmd.exe to execute commands on the victim’s machine.(Citation: Unit 42 RGDoor Jan 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d467445-9cce-4e84-968e-7a7ecc0a81fa`.

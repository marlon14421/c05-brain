---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0488"
target_object: "T1016"
stix_relationship_id: "relationship--de55c190-81ee-49b8-a279-1692725ea6cc"
---
# Relationship 9160: S0488 — uses → T1016

**Source object:** [[01 ATT&CK/S0488 - CrackMapExec|S0488: CrackMapExec]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CrackMapExec](https://attack.mitre.org/software/S0488) can collect DNS information from the targeted system.(Citation: CME Github September 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--de55c190-81ee-49b8-a279-1692725ea6cc`.

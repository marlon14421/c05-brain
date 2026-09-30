---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0091"
target_object: "T1082"
stix_relationship_id: "relationship--66b026b6-af1e-47a6-9c3d-b853e2130b68"
---
# Relationship 7949: S0091 — uses → T1082

**Source object:** [[01 ATT&CK/S0091 - Epic|S0091: Epic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Epic](https://attack.mitre.org/software/S0091) collects the OS version, hardware information, computer name, available system memory status, and system and user language settings.(Citation: Kaspersky Turla Aug 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66b026b6-af1e-47a6-9c3d-b853e2130b68`.

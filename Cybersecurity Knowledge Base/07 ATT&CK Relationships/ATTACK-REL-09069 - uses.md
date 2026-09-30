---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0267"
target_object: "T1112"
stix_relationship_id: "relationship--321c1e2e-c295-42db-87cf-4d71f6c7f164"
---
# Relationship 9069: S0267 — uses → T1112

**Source object:** [[01 ATT&CK/S0267 - FELIXROOT|S0267: FELIXROOT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FELIXROOT](https://attack.mitre.org/software/S0267) deletes the Registry key HKCU\Software\Classes\Applications\rundll32.exe\shell\open .(Citation: FireEye FELIXROOT July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--321c1e2e-c295-42db-87cf-4d71f6c7f164`.

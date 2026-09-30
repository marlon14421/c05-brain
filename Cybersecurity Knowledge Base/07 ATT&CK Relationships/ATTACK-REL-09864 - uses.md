---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0031"
target_object: "T1057"
stix_relationship_id: "relationship--64cb753d-eb72-4dce-a417-7df747334347"
---
# Relationship 9864: S0031 — uses → T1057

**Source object:** [[01 ATT&CK/S0031 - BACKSPACE|S0031: BACKSPACE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BACKSPACE](https://attack.mitre.org/software/S0031) may collect information about running processes.(Citation: FireEye APT30)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--64cb753d-eb72-4dce-a417-7df747334347`.

---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0567"
target_object: "T1129"
stix_relationship_id: "relationship--e07d9070-6989-43e7-aee0-1b18aff1ffbe"
---
# Relationship 8089: S0567 — uses → T1129

**Source object:** [[01 ATT&CK/S0567 - Dtrack|S0567: Dtrack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1129 - Shared Modules|T1129: Shared Modules]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dtrack](https://attack.mitre.org/software/S0567) contains a function that calls LoadLibrary and GetProcAddress .(Citation: CyberBit Dtrack)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e07d9070-6989-43e7-aee0-1b18aff1ffbe`.

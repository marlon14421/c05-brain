---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1159"
target_object: "T1087.001"
stix_relationship_id: "relationship--57bf3d4d-788c-43f9-b35b-a76b68a0b02d"
---
# Relationship 6975: S1159 — uses → T1087.001

**Source object:** [[01 ATT&CK/S1159 - DUSTTRAP|S1159: DUSTTRAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DUSTTRAP](https://attack.mitre.org/software/S1159) can enumerate local user accounts.(Citation: Google Cloud APT41 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--57bf3d4d-788c-43f9-b35b-a76b68a0b02d`.

---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0414"
target_object: "T1218.005"
stix_relationship_id: "relationship--3759c775-300f-4981-9264-722ecf97aa64"
---
# Relationship 6510: S0414 — uses → T1218.005

**Source object:** [[01 ATT&CK/S0414 - BabyShark|S0414: BabyShark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.005 - Mshta|T1218.005: Mshta]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BabyShark](https://attack.mitre.org/software/S0414) has used mshta.exe to download and execute applications from a remote server.(Citation: CISA AA20-301A Kimsuky)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3759c775-300f-4981-9264-722ecf97aa64`.

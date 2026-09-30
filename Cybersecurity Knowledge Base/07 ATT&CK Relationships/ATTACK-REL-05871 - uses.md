---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9026"
target_object: "T1497.002"
stix_relationship_id: "relationship--907493b8-a53a-4aca-8b80-28dfaa63dec8"
---
# Relationship 5871: S9026 — uses → T1497.002

**Source object:** [[01 ATT&CK/S9026 - ROAMINGHOUSE|S9026: ROAMINGHOUSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.002 - User Activity Based Checks|T1497.002: User Activity Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ROAMINGHOUSE](https://attack.mitre.org/software/S9026) can check for specific mouse movements and user activity before initiating malicious activity.(Citation: Trend Micro Earth Kasha Anel NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--907493b8-a53a-4aca-8b80-28dfaa63dec8`.

---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0066"
target_object: "T1071.001"
stix_relationship_id: "relationship--2d659138-90e5-4b67-8956-02120d99506f"
---
# Relationship 9776: S0066 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0066 - 3PARA RAT|S0066: 3PARA RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[3PARA RAT](https://attack.mitre.org/software/S0066) uses HTTP for command and control.(Citation: CrowdStrike Putter Panda)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d659138-90e5-4b67-8956-02120d99506f`.

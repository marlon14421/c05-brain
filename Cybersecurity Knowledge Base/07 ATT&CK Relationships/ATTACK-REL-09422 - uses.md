---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1210"
target_object: "T1041"
stix_relationship_id: "relationship--0977de2b-86f0-4c40-bd6f-9c54ad1a56c0"
---
# Relationship 9422: S1210 — uses → T1041

**Source object:** [[01 ATT&CK/S1210 - Sagerunex|S1210: Sagerunex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sagerunex](https://attack.mitre.org/software/S1210) encrypts collected system data then exfiltrates via existing command and control channels.(Citation: Cisco LotusBlossom 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0977de2b-86f0-4c40-bd6f-9c54ad1a56c0`.

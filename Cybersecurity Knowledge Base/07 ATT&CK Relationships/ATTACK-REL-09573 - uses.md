---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1247"
target_object: "T1135"
stix_relationship_id: "relationship--7ed71499-07cb-4cea-9a7e-5822a69b28e3"
---
# Relationship 9573: S1247 — uses → T1135

**Source object:** [[01 ATT&CK/S1247 - Embargo|S1247: Embargo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Embargo](https://attack.mitre.org/software/S1247) has searched for folders, subfolders and other networked or mounted drives for follow-on encryption actions.(Citation: Cyble Embargo Ransomware May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ed71499-07cb-4cea-9a7e-5822a69b28e3`.

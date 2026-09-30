---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1009"
target_object: "T1587.001"
stix_relationship_id: "relationship--8b9d30d9-7546-4fc0-87cb-1e432fe788e8"
---
# Relationship 6358: G1009 — uses → T1587.001

**Source object:** [[01 ATT&CK/G1009 - Moses Staff|G1009: Moses Staff]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.001 - Malware|T1587.001: Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Moses Staff](https://attack.mitre.org/groups/G1009) has built malware, such as [DCSrv](https://attack.mitre.org/software/S1033) and [PyDCrypt](https://attack.mitre.org/software/S1032), for targeting victims' machines.(Citation: Checkpoint MosesStaff Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b9d30d9-7546-4fc0-87cb-1e432fe788e8`.

---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1050"
target_object: "T1041"
stix_relationship_id: "relationship--c7f04f79-4bda-4abf-8f74-4faad8a09f19"
---
# Relationship 6586: S1050 — uses → T1041

**Source object:** [[01 ATT&CK/S1050 - PcShare|S1050: PcShare]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PcShare](https://attack.mitre.org/software/S1050) can upload files and information from a compromised host to its C2 servers.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c7f04f79-4bda-4abf-8f74-4faad8a09f19`.

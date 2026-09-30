---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1089"
target_object: "T1041"
stix_relationship_id: "relationship--7b28dace-9c62-4226-9878-dee480f541d4"
---
# Relationship 5928: S1089 — uses → T1041

**Source object:** [[01 ATT&CK/S1089 - SharpDisco|S1089: SharpDisco]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SharpDisco](https://attack.mitre.org/software/S1089) can load a plugin to exfiltrate stolen files to SMB shares also used in C2.(Citation: MoustachedBouncer ESET August 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b28dace-9c62-4226-9878-dee480f541d4`.

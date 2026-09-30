---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0147"
target_object: "T1070.004"
stix_relationship_id: "relationship--c8bceb4a-0cf2-43c9-9729-20ed706c4c72"
---
# Relationship 6146: S0147 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0147 - Pteranodon|S0147: Pteranodon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pteranodon](https://attack.mitre.org/software/S0147) can delete files that may interfere with it executing. It also can delete temporary files and itself after the initial script executes.(Citation: Palo Alto Gamaredon Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8bceb4a-0cf2-43c9-9729-20ed706c4c72`.

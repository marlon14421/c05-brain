---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1138"
target_object: "T1132.001"
stix_relationship_id: "relationship--b1b17a6e-991a-4ead-aedd-c7b1f09ce17c"
---
# Relationship 5618: S1138 — uses → T1132.001

**Source object:** [[01 ATT&CK/S1138 - Gootloader|S1138: Gootloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gootloader](https://attack.mitre.org/software/S1138) can retrieve a Base64 encoded stager from C2.(Citation: SentinelOne Gootloader June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1b17a6e-991a-4ead-aedd-c7b1f09ce17c`.

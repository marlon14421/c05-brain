---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0625"
target_object: "T1057"
stix_relationship_id: "relationship--c253f0c5-1802-4853-b93f-c426d2a48fae"
---
# Relationship 6730: S0625 — uses → T1057

**Source object:** [[01 ATT&CK/S0625 - Cuba|S0625: Cuba]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cuba](https://attack.mitre.org/software/S0625) can enumerate processes running on a victim's machine.(Citation: McAfee Cuba April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c253f0c5-1802-4853-b93f-c426d2a48fae`.

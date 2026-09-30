---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0219"
target_object: "T1057"
stix_relationship_id: "relationship--149a056e-9061-4345-a46a-c1f73653d16a"
---
# Relationship 5681: S0219 — uses → T1057

**Source object:** [[01 ATT&CK/S0219 - WINERACK|S0219: WINERACK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WINERACK](https://attack.mitre.org/software/S0219) can enumerate processes.(Citation: FireEye APT37 Feb 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--149a056e-9061-4345-a46a-c1f73653d16a`.

---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0201"
target_object: "T1685"
stix_relationship_id: "relationship--08ced821-8f14-4c59-ba35-d5d836b3f7b8"
---
# Relationship 7179: S0201 — uses → T1685

**Source object:** [[01 ATT&CK/S0201 - JPIN|S0201: JPIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[JPIN](https://attack.mitre.org/software/S0201) can lower security settings by changing Registry keys.(Citation: Microsoft PLATINUM April 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08ced821-8f14-4c59-ba35-d5d836b3f7b8`.

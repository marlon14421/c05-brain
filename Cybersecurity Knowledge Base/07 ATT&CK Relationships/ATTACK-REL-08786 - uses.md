---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0002"
target_object: "S0110"
stix_relationship_id: "relationship--a4d7be79-1cb7-4009-84d0-165cb6c7fcc6"
---
# Relationship 8786: C0002 — uses → S0110

**Source object:** [[01 ATT&CK/C0002 - Night Dragon|C0002: Night Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0110 - at|S0110: at]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Night Dragon](https://attack.mitre.org/campaigns/C0002), threat actors used [at](https://attack.mitre.org/software/S0110) to execute droppers.(Citation: McAfee Night Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a4d7be79-1cb7-4009-84d0-165cb6c7fcc6`.

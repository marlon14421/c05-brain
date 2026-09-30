---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0014"
target_object: "S0645"
stix_relationship_id: "relationship--49dd9dc3-b0b8-499f-8fad-177779d494df"
---
# Relationship 5421: C0014 — uses → S0645

**Source object:** [[01 ATT&CK/C0014 - Operation Wocao|C0014: Operation Wocao]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0645 - Wevtutil|S0645: Wevtutil]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Wocao](https://attack.mitre.org/campaigns/C0014), threat actors used [Wevtutil](https://attack.mitre.org/software/S0645) to delete system and security event logs with `wevtutil cl system` and `wevtutil cl security`.(Citation: FoxIT Wocao December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49dd9dc3-b0b8-499f-8fad-177779d494df`.

---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0466"
target_object: "T1119"
stix_relationship_id: "relationship--7a6c1581-a077-4c8f-8111-3264fa9e1e9c"
---
# Relationship 8868: S0466 — uses → T1119

**Source object:** [[01 ATT&CK/S0466 - WindTail|S0466: WindTail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WindTail](https://attack.mitre.org/software/S0466) can identify and add files that possess specific file extensions to an array for archiving.(Citation: objective-see windtail2 jan 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a6c1581-a077-4c8f-8111-3264fa9e1e9c`.

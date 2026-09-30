---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0013"
target_object: "T1559.002"
stix_relationship_id: "relationship--14acc004-9b77-4a4a-b31d-a8eea459b4bb"
---
# Relationship 8021: C0013 — uses → T1559.002

**Source object:** [[01 ATT&CK/C0013 - Operation Sharpshooter|C0013: Operation Sharpshooter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.002 - Dynamic Data Exchange|T1559.002: Dynamic Data Exchange]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Sharpshooter](https://attack.mitre.org/campaigns/C0013), threat actors sent malicious Word OLE documents to victims.(Citation: McAfee Sharpshooter December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--14acc004-9b77-4a4a-b31d-a8eea459b4bb`.

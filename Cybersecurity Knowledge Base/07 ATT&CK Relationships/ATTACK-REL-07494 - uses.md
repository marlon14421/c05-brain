---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0006"
target_object: "T1560.001"
stix_relationship_id: "relationship--973ed739-22d9-433f-ba63-f4881639a22d"
---
# Relationship 7494: C0006 — uses → T1560.001

**Source object:** [[01 ATT&CK/C0006 - Operation Honeybee|C0006: Operation Honeybee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Honeybee](https://attack.mitre.org/campaigns/C0006), the threat actors uses zip to pack collected files before exfiltration.(Citation: McAfee Honeybee)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--973ed739-22d9-433f-ba63-f4881639a22d`.

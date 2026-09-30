---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1019"
target_object: "T1059.007"
stix_relationship_id: "relationship--396056dc-8657-418c-9c7a-4468878af204"
---
# Relationship 9764: G1019 — uses → T1059.007

**Source object:** [[01 ATT&CK/G1019 - MoustachedBouncer|G1019: MoustachedBouncer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MoustachedBouncer](https://attack.mitre.org/groups/G1019) has used JavaScript to deliver malware hosted on HTML pages.(Citation: MoustachedBouncer ESET August 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--396056dc-8657-418c-9c7a-4468878af204`.

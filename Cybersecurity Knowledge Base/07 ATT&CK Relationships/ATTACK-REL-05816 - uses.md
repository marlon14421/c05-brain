---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0070"
target_object: "T1113"
stix_relationship_id: "relationship--ec8f73de-eab1-4d3b-88c0-7885716aa748"
---
# Relationship 5816: G0070 — uses → T1113

**Source object:** [[01 ATT&CK/G0070 - Dark Caracal|G0070: Dark Caracal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dark Caracal](https://attack.mitre.org/groups/G0070) took screenshots using their Windows malware.(Citation: Lookout Dark Caracal Jan 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec8f73de-eab1-4d3b-88c0-7885716aa748`.

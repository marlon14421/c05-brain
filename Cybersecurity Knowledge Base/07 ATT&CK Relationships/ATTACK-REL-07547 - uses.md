---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1087"
target_object: "T1125"
stix_relationship_id: "relationship--84094d38-2a22-4d9a-b570-72e45baf17ab"
---
# Relationship 7547: S1087 — uses → T1125

**Source object:** [[01 ATT&CK/S1087 - AsyncRAT|S1087: AsyncRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AsyncRAT](https://attack.mitre.org/software/S1087) can record screen content on targeted systems.(Citation: AsyncRAT GitHub)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--84094d38-2a22-4d9a-b570-72e45baf17ab`.

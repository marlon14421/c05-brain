---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1087"
target_object: "T1113"
stix_relationship_id: "relationship--ed592480-2e4d-4604-aa8d-89bf58d72f6b"
---
# Relationship 5666: S1087 — uses → T1113

**Source object:** [[01 ATT&CK/S1087 - AsyncRAT|S1087: AsyncRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AsyncRAT](https://attack.mitre.org/software/S1087) has the ability to view the screen on compromised hosts.(Citation: AsyncRAT GitHub)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed592480-2e4d-4604-aa8d-89bf58d72f6b`.

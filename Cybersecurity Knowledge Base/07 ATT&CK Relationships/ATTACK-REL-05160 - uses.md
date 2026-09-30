---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0098"
target_object: "T1113"
stix_relationship_id: "relationship--dd89d8a2-257a-47f9-8b55-8011ca53007b"
---
# Relationship 5160: S0098 — uses → T1113

**Source object:** [[01 ATT&CK/S0098 - T9000|S0098: T9000]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[T9000](https://attack.mitre.org/software/S0098) can take screenshots of the desktop and target application windows, saving them to user directories as one byte XOR encrypted .dat files.(Citation: Palo Alto T9000 Feb 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd89d8a2-257a-47f9-8b55-8011ca53007b`.

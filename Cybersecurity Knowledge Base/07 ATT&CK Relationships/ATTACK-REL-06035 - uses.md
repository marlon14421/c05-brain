---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0143"
target_object: "T1123"
stix_relationship_id: "relationship--07d16181-ba82-42c8-a67b-8d7d5adef52d"
---
# Relationship 6035: S0143 — uses → T1123

**Source object:** [[01 ATT&CK/S0143 - Flame|S0143: Flame]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1123 - Audio Capture|T1123: Audio Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Flame](https://attack.mitre.org/software/S0143) can record audio using any existing hardware recording devices.(Citation: Kaspersky Flame)(Citation: Kaspersky Flame Functionality)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--07d16181-ba82-42c8-a67b-8d7d5adef52d`.

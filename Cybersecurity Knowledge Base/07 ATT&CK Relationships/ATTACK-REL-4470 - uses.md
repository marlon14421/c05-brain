---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0192"
target_object: "T1125"
stix_relationship_id: "relationship--c18f83e7-979e-4bd8-80bb-d0a4e8146a21"
---
# Relationship 4470: S0192 — uses → T1125

**Source object:** [[01 ATT&CK/S0192 - Pupy|S0192: Pupy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pupy](https://attack.mitre.org/software/S0192) can access a connected webcam and capture pictures.(Citation: GitHub Pupy)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c18f83e7-979e-4bd8-80bb-d0a4e8146a21`.

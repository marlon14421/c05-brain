---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0336"
target_object: "T1125"
stix_relationship_id: "relationship--1efc9685-b2ab-46fb-91a9-a305d6c1f335"
---
# Relationship 3135: S0336 — uses → T1125

**Source object:** [[01 ATT&CK/S0336 - NanoCore|S0336: NanoCore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NanoCore](https://attack.mitre.org/software/S0336) can access the victim's webcam and capture data.(Citation: DigiTrust NanoCore Jan 2017)(Citation: PaloAlto NanoCore Feb 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1efc9685-b2ab-46fb-91a9-a305d6c1f335`.

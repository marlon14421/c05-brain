---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1185"
target_object: "T1113"
stix_relationship_id: "relationship--357dc150-9787-4b39-b18a-a0a38778a44f"
---
# Relationship 4882: S1185 — uses → T1113

**Source object:** [[01 ATT&CK/S1185 - LightSpy|S1185: LightSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LightSpy](https://attack.mitre.org/software/S1185) uses Apple's built-in AVFoundation Framework library to access the user's camera and screen. It uses the `AVCaptureStillImage` to take a picture using the user's camera and the `AVCaptureScreen` to take a screenshot or record the user's screen for a specified period of time.(Citation: Huntress LightSpy macOS 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--357dc150-9787-4b39-b18a-a0a38778a44f`.

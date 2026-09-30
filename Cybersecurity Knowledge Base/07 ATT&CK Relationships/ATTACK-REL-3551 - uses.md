---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1234"
target_object: "T1082"
stix_relationship_id: "relationship--08b94d01-f4c1-4692-aa39-a203fd97d581"
---
# Relationship 3551: S1234 — uses → T1082

**Source object:** [[01 ATT&CK/S1234 - SplatCloak|S1234: SplatCloak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SplatCloak](https://attack.mitre.org/software/S1234) has collected the Windows build number using the windows kernel API `RtlGetVersion` to determine if the response is 19000 or higher (Windows 10 version 2004 or later).(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08b94d01-f4c1-4692-aa39-a203fd97d581`.

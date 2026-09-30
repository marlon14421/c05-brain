---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0035"
target_object: "T1113"
stix_relationship_id: "relationship--08b30f76-ca12-4d2c-9345-ee51bfd54e9f"
---
# Relationship 3870: G0035 — uses → T1113

**Source object:** [[01 ATT&CK/G0035 - Dragonfly|G0035: Dragonfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Dragonfly](https://attack.mitre.org/groups/G0035) has performed screen captures of victims, including by using a tool, scr.exe (which matched the hash of ScreenUtil).(Citation: US-CERT TA18-074A)(Citation: Symantec Dragonfly Sept 2017)(Citation: Gigamon Berserk Bear October 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08b30f76-ca12-4d2c-9345-ee51bfd54e9f`.

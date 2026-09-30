---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1201"
target_object: "T1113"
stix_relationship_id: "relationship--924b50a5-3fae-496c-8167-610fa261a10f"
---
# Relationship 3029: S1201 — uses → T1113

**Source object:** [[01 ATT&CK/S1201 - TRANSLATEXT|S1201: TRANSLATEXT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TRANSLATEXT](https://attack.mitre.org/software/S1201) has the ability to capture screenshots of new browser tabs, based on the presence of the `Capture` flag.(Citation: Zscaler Kimsuky TRANSLATEXT)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--924b50a5-3fae-496c-8167-610fa261a10f`.

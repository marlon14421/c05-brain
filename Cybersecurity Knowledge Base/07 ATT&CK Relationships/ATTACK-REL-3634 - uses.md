---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1130"
target_object: "T1685"
stix_relationship_id: "relationship--0ae86b10-69a4-4e9d-9b31-403dc08be50f"
---
# Relationship 3634: S1130 — uses → T1685

**Source object:** [[01 ATT&CK/S1130 - Raspberry Robin|S1130: Raspberry Robin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Raspberry Robin](https://attack.mitre.org/software/S1130) can add an exception to Microsoft Defender that excludes the entire main drive from anti-malware scanning to evade detection.(Citation: HP RaspberryRobin 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0ae86b10-69a4-4e9d-9b31-403dc08be50f`.

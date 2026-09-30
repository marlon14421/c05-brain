---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1167"
target_object: "T1529"
stix_relationship_id: "relationship--30c9b855-cb8e-43ab-8f4c-ffef015789d6"
---
# Relationship 4912: S1167 — uses → T1529

**Source object:** [[01 ATT&CK/S1167 - AcidPour|S1167: AcidPour]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1529 - System Shutdown-Reboot|T1529: System Shutdown/Reboot]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AcidPour](https://attack.mitre.org/software/S1167) includes functionality to reboot the victim system following wiping actions, similar to [AcidRain](https://attack.mitre.org/software/S1125).(Citation: SentinelOne AcidPour 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30c9b855-cb8e-43ab-8f4c-ffef015789d6`.

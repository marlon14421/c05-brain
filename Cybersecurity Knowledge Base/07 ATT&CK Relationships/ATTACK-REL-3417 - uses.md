---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1125"
target_object: "T1561.001"
stix_relationship_id: "relationship--5cfbd739-de51-4a86-b116-8a8fc09c387f"
---
# Relationship 3417: S1125 — uses → T1561.001

**Source object:** [[01 ATT&CK/S1125 - AcidRain|S1125: AcidRain]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.001 - Disk Content Wipe|T1561.001: Disk Content Wipe]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AcidRain](https://attack.mitre.org/software/S1125) iterates over device file identifiers on the target, opens the device file, and either overwrites the file or calls various IOCTLS commands to erase it.(Citation: AcidRain JAGS 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5cfbd739-de51-4a86-b116-8a8fc09c387f`.

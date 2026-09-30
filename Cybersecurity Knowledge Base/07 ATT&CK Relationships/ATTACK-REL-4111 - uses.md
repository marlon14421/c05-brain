---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0674"
target_object: "T1082"
stix_relationship_id: "relationship--0586324a-680a-46a4-917b-8c00c7211065"
---
# Relationship 4111: S0674 — uses → T1082

**Source object:** [[01 ATT&CK/S0674 - CharmPower|S0674: CharmPower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CharmPower](https://attack.mitre.org/software/S0674) can enumerate the OS version and computer name on a targeted system.(Citation: Check Point APT35 CharmPower January 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0586324a-680a-46a4-917b-8c00c7211065`.

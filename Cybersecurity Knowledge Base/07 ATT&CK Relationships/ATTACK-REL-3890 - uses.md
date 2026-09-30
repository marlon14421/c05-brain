---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0496"
target_object: "T1112"
stix_relationship_id: "relationship--2c927351-d98a-4734-83db-82ad3231e59f"
---
# Relationship 3890: S0496 — uses → T1112

**Source object:** [[01 ATT&CK/S0496 - REvil|S0496: REvil]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[REvil](https://attack.mitre.org/software/S0496) can modify the Registry to save encryption parameters and system information.(Citation: Cylance Sodinokibi July 2019)(Citation: Secureworks GandCrab and REvil September 2019)(Citation: McAfee Sodinokibi October 2019)(Citation: Intel 471 REvil March 2020)(Citation: Secureworks REvil September 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2c927351-d98a-4734-83db-82ad3231e59f`.
